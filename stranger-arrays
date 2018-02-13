use_bpm 160
use_synth :blade
st_notes = [:c2, :e2, :g2, :b2, :c3, :b2, :g2, :e2] #this is a list, aka an array, of the notes we will be using for the song
index = 0

live_loop :main do
  8.times do
    play st_notes[index]
    sleep 0.5
    index = index + 1
  end
  #once the notes are played 8 times, we have to set the index variable back to 0 therefore allowing the notes to continuously play within the live loop
  index = 0
end

live_loop :melody do
  use_bpm 80
  with_synth :saw do
    play :d, amp: 0.2
    sleep 0.5
    play :e, amp: 0.2
    sleep 0.5
    play :g, amp: 0.2
    sleep 0.5
    play :b, amp: 0.2
    sleep 0.5
    play :c, amp: 0.2
    sleep 0.5
    play :b, amp: 0.2
    sleep 0.5
    play :g, amp: 0.2
    sleep 0.5
    play :e, amp: 0.2
    sleep 0.5
  end
end
