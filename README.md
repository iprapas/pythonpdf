# pythonpdf

Stamping pdf files, using python libraries [PyPDF2][1] and [reportlab][2]

## Requirements

python 2.7  
PyPDF2  
qrcode  (to run example)  


```
pip install -r requirements.txt
```

[1]: https://pythonhosted.org/PyPDF2/
[2]: http://www.reportlab.com/

## Run script
```
cd src
python stamp.py
```

## Check the results
Input in the *input/* folder  
Results can be found in *output/* folder  

## And now PLAY
You can easily modify the code in *src/stamp.py*, make your own pdf stamps and stamp your pdfs!  

## Problems merging pages with PyPDF2
- The metadata are not passed from the original pdf to the stamped one.
- Bookmarks are not kept either.
