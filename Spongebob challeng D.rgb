# CHALLENGE D: Use functions to optimize the SpongeBob theme!

use_bpm 136
use_synth :pretty_bell

live_loop :sb do
  sample :bass_hit_c, amp: 3
  sleep 2
end
live_loop :sb do
  16. times do
    sample :bass_hit_c, amp: 3
    sleep 2
  end
  stop
end
define :sponge1 do
  play :r
  sleep 1
  play:E5
  play:Gs4
  play:B4
  sleep 1
  play:B4
  sleep 1
  play:E5
  play:Gs4
  sleep 1
end
define :sponge2 do
  play:B4
  sleep 0.75
  play:As4
  sleep 0.25
  play:Gs4
  play:B4
  sleep 0.75
  play:Cs5
  sleep 0.25
  play:B4
  sleep 1
  play:Gs4
  play:E5
  sleep 1
end
live_loop:background_notes do
  play:E3, amp: 0.25
  sleep 1
  play:B3, amp: 0.25
  play:E4, amp: 0.25
  sleep 1
  play:B3, amp: 0.25
  sleep 1
  play:E4, amp: 0.25
  sleep 1
  
  play:E3, amp: 0.5
  sleep 1
  play:B3, amp: 0.5
  play:E4, amp: 0.5
  sleep 1
  play:B3, amp: 0.5
  sleep 1
  play:E4, amp: 0.5
  sleep 1
  
  play:E3, amp: 0.75
  sleep 1
  play:B3, amp: 0.75
  play:E4, amp: 0.75
  sleep 1
  play:B3, amp: 0.75
  sleep 1
  play:E4, amp: 0.75
  sleep 1
  
  5.times do
    play:E3, amp: 1
    sleep 1
    play:B3, amp: 1
    play:E4, amp: 1
    sleep 1
    play:B3, amp: 1
    sleep 1
    play:E4, amp: 1
    sleep 1
  end
  stop
end
# Measure 1
with_fx :vowel do
  sponge1
end
# Measure 2
define :sponge do
  play:E4
  sleep 1
  play:E5
  play:Gs4
  sleep 2
  play:E5
  play:Gs4
  sleep 1
end
# Measure 3 SAME

sponge1
# Measure 4 SAME
with_fx :vowel do
  sponge1
end
# Measure 5
sponge2
# Measure 6 SAME
with_fx :pan do
  sponge1
end
# Measure 7
with_fx :vowel do
  sponge2
end
sample_duration :drum_cymbal_soft, amp: 6
sample :drum_cymbal_soft, amp: 3
# Measure 8
with_fx :vowel do
  sponge
end
sample :drum_bass_soft, amp: 6
sample :drum_bass_hard, amp: 6
