# whisper-ai-hackfest
Work done during the whisper-ai-hackfest at Mcmaster University in Hamilton

This was completed through the assistance of following these guides https://lablab.ai/tech/openai/whisper
The lab I used was specficially about speaker identification https://lablab.ai/t/whisper-transcription-and-speaker-identification

1: Follow the steps getting ffmpeg onto you machine, and after that continue till you get a .wav file, id suggest adjusting the size of your file unless you the gpu's to handle larger files
2: At this point you'll run into pyannote to which is where we handle the diarization of the files. It is open source python tool that you'll need to sign up at https://huggingface.co/pyannote/speaker-diarization-3.1 and follow the readme and sign up to get an access token. 
3: I personally sperated out a few of the python files to it was less cluttered but from this step forward you'll want to include all files into one python file.
