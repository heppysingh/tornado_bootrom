# tornado_bootro

This contains the required files to bypass Download Agent Authentication and Serial Link authentication and allows you to unbrick your devices without using paid tools 
Works on Devices with codename `tornado`:-  
- Redmi 15C 5G  
- Redmi 15R 5G  
- Redmi 17C 5G  
- POCO C85 5G   
Usage instructions :-  
Install mtkclient on your computer   
```
python3 mtk.py printgpt --stock --loader ~/DA_BR.bin --preloader ~/preloader_tornado.bin --auth ~/auth_sv5.auth
```

