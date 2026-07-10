## max-osc-speaker-coordinates
When the print_speaker_coordinates script is run, this prints x, y, and z coordinates of speaker locations in osc command format to your terminal. For use with max spat5 library, where defining speaker coordinates for spatial audio is necessary.\


##### Assumptions & Limitations:
- Speaker modules are assumed to be identical 
- Speaker modules are assumed to have the same number of speakers in each row
- The distance between speakers within a module along the y-axis are assumed to be constant\

Additionally, this coordinate generation script is best for large, multichannel (16+ channel) audio setups where each speaker module is identical. It is not ideal for smaller scale audio setups. Additionally, this script is intended to be used for debugging/demo purposes.

