# Twinkle-Twinkle-Song-using-MATLAB
%TWINKLE TWINKLE WITH SARGAM
% Frequencies of musical notes (in Hz)
sa = 240;
re = 270;
ga = 300;
ma = 320;
pa = 360;
dha = 400;
% Sample rate and duration for each note
Fs = 4000;    % Sampling frequency (samples per second)
ts=1/Fs;
duration=0.4;
t = 0:ts:duration;
twinklesa=sin(2*pi*sa*t);
twinklere=sin(2*pi*re*t);
twinklega=sin(2*pi*ga*t);
twinklema=sin(2*pi*ma*t);
twinklepa=sin(2*pi*pa*t);
twinkledha=sin(2*pi*dha*t);
melody1=[twinklesa, twinklesa, twinklepa, twinklepa, twinkledha, twinkledha, twinklepa];
melody2=[twinklema, twinklema, twinklega, twinklega, twinklere, twinklere, twinklesa];
melody3=[twinklepa, twinklepa, twinklema, twinklema, twinklega, twinklega, twinklere];
melody4=[twinklema, twinklema, twinklega, twinklega, twinklere, twinklere, twinklesa];
% Play the melody for "Twinkle Twinkle Little Star" with pauses
sound(melody1, Fs); % Twinkle, twinkle little star
pause(2);
sound(melody2, Fs); % How I wonder what you are
pause(2);
sound(melody3, Fs); % Up above so what so high
pause(2);
sound(melody4, Fs); % like a daimond in the sky
pause(5);
