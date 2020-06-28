# MATLAB-Music
Use the function sound() to create music.

HOW TO PLAY: 
1. Download snd.m, tone.m and one of the main music programs (BJDJSS, YJM or KAWAHTAAAA).
2. Run the main music program.

The files with capitalized letters are the main music programs.
I've uploaded 3 test songs:君は蔷薇より美しい(KAWAHTAAAA), 北京的金山上(BJDJSS) and 一剪梅(YJM).
You could use these models to create your music.

The files with uncapitalized letters are the sub-programs.
All sounds are generated by the function snd(tone,pitch,rythm,fs) in snd.m.
  Tones: 1,2,3,4,5,6,7 represent C,D,E,F,G,A,B in music;
         8 for stop
  Pitch: 0 for base, 1,2,3... for higher tone, and -1,-2,-3... for lower tones ; 
  rythm: 1 for base, bigger the number, longer the rythm.
  fs: Sampling frequency. Commonly 8192 Hz.
         
For convenience, I created a tone library in tone.m.
All tones are in this sequence: tone + pitch + rythm.
  Tones: d,r,m,f,s,l,c represent C,D,E,F,G,A,B in music,
         x for stop;
  Pitch: 'h' for Higher tones, 'l' for lower tones; 
  rythm: '1' for 2 times longer rythm, '11' for 4 times longer rythm,
         '0' for 2 times shorter rythm, '00' for 4 times shorter rythm;
E.g.  'dh1' for C in higher tone  for longer rythm;
      'll0' for A in lower tone for shorter rythm;
      'm' for E in base tone for base rythm.
