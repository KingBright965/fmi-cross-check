Model:
      Example with triggered subsystems and different trigger types.
      
      FMI Type:
      ModelExchange
      
      Generation Tool:
      Dassault Systemes FMU Export from Simulink, ver. 2.1 (MATLAB 8.7 (R2014b) 08-Sep-2014)
      
      Available Platforms:
      win32, win64
      
      Known Errors:
      
      Additional Information:
      
      
        
      FMUChecker:
      FMUChecker Version 2.0.2b1
      
      run command:
      set FMUName=TriggeredSubsystems_sf
      fmuCheck.win64.exe -k me -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 1e-3 -s 10 %FMUName%.fmu
      
      Contact info: dan.henriksson@3ds.com
