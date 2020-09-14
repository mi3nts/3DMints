# 3DMints

## Setting Up Monoprice Delta Pro on Cura 
- Download and Install Cura from [Cura](https://ultimaker.com/software/ultimaker-cura).
- Open Cura and go to Preferences> Configure Cura 
  - Add Monoprice [Delta Pro Profile](https://github.com/mi3nts/3DMints/blob/master/res/delta%20pro%20profile.curaprofile?raw=true)
- Open Settings > Printer > Add Printer > Non Networked Printer > Custom FFF Printer 
  - On the right Hand Tab type printer name as Monoprice Delta Pro 
  - The said printer should have the attributes given below: 
       - Printer Tab 
       
            X Width 270
            Y Depth 270
            Z Height 340

            Build plate shape - Circular/ Elliptic 
            Origin At Center Checked 
            Heated Bed Checked 

            Print head settings leave as is 

       -  Extruder1 Tab 
       
            Nozzle size 0.4mm 
            Compatible Material Diameter 1.75

- Open Settings > Extruder 1 > Materials > Manage Materials 
    - On the right hand pane under custom material fill in the following:
 <br/>
    ![Custom Printer 1](https://github.com/mi3nts/3DMints/blob/master/res/customize1.png)
    ![Custom Printer 2](https://raw.githubusercontent.com/mi3nts/3DMints/master/res/cuztomize2.png)
      
-  Change All settings 
    - On the right hand side of the main window hit the edit icon and do the following corrections. 
     <br/>
     ![All Settings](https://github.com/mi3nts/3DMints/raw/master/res/settings.png)
    
  - Add the selcted .stl file 
    - File> Open File(s)

- Hit the slice on the bottom right hand corner and save your gcode to a preffered location.   

    

