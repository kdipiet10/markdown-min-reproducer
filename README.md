# markdown-min-reproducer

creating a minimum reproducer for creating base urls 

How to compile
```Setup
git clone git@github.com:kdipiet10/markdown-min-reproducer.git
cd markdown-min-reproducer
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
mkdocs serve
```

After running this, it will show the following:
```bash
INFO     -  [14:00:50] Serving on url/server/here
```

Copy and paste that link into a browser, navigate to the welcome page, and see how both dynamic links work. 
