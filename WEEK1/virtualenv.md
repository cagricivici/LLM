Takeaway_1: If you dont enable virtualenv, the libs installed will go under user/username/appdata/local... If you want the lib save in lib of virtualenv, you need to activate it first then pip install blablabla...

>> virtualenv firstenv
>> 
>> firstenv\Scripts> .\activate
>> 
>> pip install pandas
>> 
>> pip list (you will see exes here.)
>>
>> pip freeze > req.txt (you will see lists here that is the same with pip list)
>>
>> pip install -r req.txt (install all exes stored here!)
>>
>> pip install ipykernel
>>
>> python -m ipykernel install --user --name=firstenv (set a kernel for noteboo)
---------------------------------------------------------------------------------------------------------------------------- 
 
 you will see: Installed kernelspec firstenv in C:\Users\civici\AppData\Roaming\jupyter\kernels\firstenv

everything is ready now. go to jypter notebook then set a kernel

>> jupyter notebook

finally:

![image](https://github.com/user-attachments/assets/cc42c740-1e00-4b0d-aec6-f85a7b03fde1)

