# What is Craig?
Craig is a multi-track voice recorder for Discord.
  
More information can be found here: https://craig.chat/  

# Self-hosting/installation
Detailed instructions on how to self-host Craig are located here: [SELFHOST.md](SELFHOST.md)

## Environment variables

The download API stores files in the `downloads` folder by default. Set the
`DOWNLOAD_DIR` environment variable to override this location. Downloaded files
are now kept indefinitely; adjust `apps/tasks/config/_default.js` if you wish to
enable automatic cleanup.
