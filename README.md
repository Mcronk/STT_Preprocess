
### Start the CLI
start: npm start

### Automatically re-run on each save of preProcess.js
dev: npm run dev


### Commands
<ul>
<li>check         (-c)   //Checks for STT compatibility on audio file size, duration, sample rate, and MIMEtype.</li>
<li>process       (-p)   //Augments files or directories of files for STT compatibility on audio file size, duration, sample rate, and MIMEtype.</li>
<li>split         (-s)   //Splits audio files over 100MB and outputs the resulting paths.</li>       
<li>extractAudio  (-ev)  //Extracts audio from video files.</li>
</ul>

### TODO
- Switch preprocess pipeline to run on directories of files
- Do we change from narrowband to broadband to accommodate arabic
- Separate video audio and all the other audioSize
- Writes a file that maintains the linkage between the audio file and video file
- Dump the entire metadata object into the object we pass on to other systems/write to a json file.

<ul>
<li>FLAC if space permits for lossless.</li>
<li>MP3 if we can afford slight compression.</li>
</ul>


<ul>
<li>CLI - Vorpal: https://github.com/dthree/vorpal</li>
<li>Dev - Nodemon: https://nodemon.io/</li>
</ul>
