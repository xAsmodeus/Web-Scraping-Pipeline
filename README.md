                                         ** Runned and Tested in Google Colab **                                           
## 🎯 Context

Internship challenge from Digiole. The task was to create, build and run a **modular scraping pipeline** that gathers verified business contact data (especially emails) from publicly available directories across selected industries.

https://www.notion.so/digiole/Scalable-Web-Scraping-Pipeline-21425969342680b7a99ef9f999a96f06

Tasks: 
- Extract company page links from a directory.
- Visit those links to collect email addresses.
- Clean, structure, and store the results in CSV files.

<img width="675" height="248" alt="image" src="https://github.com/user-attachments/assets/c0903703-ef57-4ced-a29b-aef82ffabd81" />
## Approach

In general, my MATLAB required almost no modification to run Python. There are functions such as **pyenv** that are useful for setting up Python in MATLAB, as well as **py.sys.version** for checking whether the interface is working.
## Examples
    USED: Display block, constants(input)/output blocks, Matlab Function Block.
**1. Two inputs -> adds the numbers together -> displays the result.** 

<img width="808" height="350" alt="image" src="https://github.com/user-attachments/assets/85ac40c9-0f6c-403c-9e28-14c07cd50496" />  

**2. An multiplication example with libraries (numpy) imported into Python code.**

<img width="808" height="350" alt="image" src="https://github.com/user-attachments/assets/9b227248-c62a-442e-926b-be229df70d52" />

## TEST FILES

The files in the repository are examples for you to run. 

## Observations
1) No Problem with 1 / N inputs -----> 1 / M outputs
   The MATLAB function block automatically recognizes the model's inputs/outputs through the code and thus adjusts what is needed. Then you just need to tweak variables/dimensions/connections, etc.
   
2) Simulink may not directly support the Python language. Therefore, scripts that take blocks_of_code must be written exclusively in MATLAB functions. In other words, the code must be converted from Python => MATLAB.

3) Special attention must be paid to the dimensions of the variables, otherwise the model will not run. (They can be changed by clicking on function_block > Edit Data > Symbols ( & Property Inspector). 

## References

  1. https://chatgpt.com/share/6755fced-a7b4-8001-918d-66a337f7cdb4
  
