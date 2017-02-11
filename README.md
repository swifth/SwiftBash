# SwiftBash

# Usage
1. git clone https://github.com/swifth/SwiftBash.git
2. cd SwiftBash
3. cp ~/.bash_rc ~/.bash_rc.bak
4. cp .bash_rc ~/.bash_rc
> source ~/.bash_rc
# Then all the following shortcuts takes effect.

# ---------- section 1 :: file system ----------

# Extract most know archives with one command.  extract, archive, tar
> extract [filename]

# Make and cd into directory
> mcd [directory name]

# List files in human readable format with color and without implied directories
> l

# List all folders.
1. lf
2. lsd

# hidden files , directory listing
> l.

# Recursive directory listing. tree , directory listing , sed , grep
> lr

# Jump back n directories at a time. directory traversal
1. ..
2. ...
3. ....
4. .....
5. ......

# go back x directories
> b [n]


# ---------- section 2 :: git command ----------

# Compact, colorized git log, formatting , log
> gl

# Visualise git log (like gitk, in the terminal)
> lg


# ---------- section 3 :: process command ----------

# Search for process. grep , ps , process
> tm [process name]

# Show which commands you use the most. history , commands
> freq

# Clear the terminal of it's output.  clear , terminal
> c


# ---------- section 4 :: text command ----------

# Find text in any file.  find , grep , search
> ft [filename pattern] [target search text] 


# ---------- section 5 :: system & software command ----------

# Debian quick update
# debian , update , apt , upgrade
> upgrade
