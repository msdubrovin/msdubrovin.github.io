# msdubrovin.github.io

github pages provide HOSTING FOR STATIC PAGES ONLY! PHP scripts would not run there...

See https://pages.github.com/

Use github for web page hosting

Create repo on github: msdubrovin.github.io

```
git clone git@github.com:msdubrovin/msdubrovin.github.io.git

echo "Hello World" > index.html

echo "<?php echo date('Y-m-d H:i:s'); ?>" > tstamp.php 

echo "<?php echo $_SERVER['REMOTE_ADDR']; ?>" > getip.php 
```

Then, as usually:

```
git add --all

git commit -m "Initial commit"

git push -u origin master
```

Web access: https://msdubrovin.github.io

