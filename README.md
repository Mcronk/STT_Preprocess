
Will start the CLI
start: npm start

Will automatically re-run on each save of preProcess.js
dev: npm run dev

check fileType
  if(audioType)
  //check audioformat
    -->prompt user to adjust format.
  //check audiosampling
    -->prompt user to adjust sampling
  //check filesize
    -->prompt user to split into pieces

  //prompt user to send to STT
    -->STT options
  //prompt user to send to translate
    -->rest of pipeline

not Audio?  END

//checks audio size, duration, sample rate, file format.  Advises how those will need to be adjusted
//Preprocessing checks for each of those and makes the necessary changes so STT will accept the file including audio extraction from video files.


TODO:  
Provide check command for individual checks (e.g. just sampling, just size, just filetype)
Switch preprocess pipeline to run on directories of files

//FLAC if space permits for lossless.
//MP3 if we can afford slight compression.

CLI - Vorpal: https://github.com/dthree/vorpal
Dev - Nodemon: https://nodemon.io/
