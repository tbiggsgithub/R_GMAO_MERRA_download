# GMAO_MERRA_download
Instructions for downloading GMAO/MERRA data for use with SEBAL

Metadata for GMAO-MERRA is at http://disc.sci.gsfc.nasa.gov/mdisc/documentation/README.MERRA.pdf

Grids are 2/3 degree latitude x 1/2 degree latitude

Go to website:  http://disc.gsfc.nasa.gov/SSW/

 Click "Select Data Sets", expand "Goddard Earth Sciences Data and Information Services Center"
    -->  MERRA
    
    choose both 
    
	1 MAT1NXRAD
  	2 MAT1NXSLV  (Wind, temp)
  	
  Click "Choose"
  
  Select dates and geographic area of interest
  
  Click on the + in front of "Subset: Spatial Region..."
  
  In list of variables, select 
  
	  MAT1NXRAD
		  Absorbed longwave at the surface LWGAB = LWin
		  Diffuse beam VIS-UV surface albedo  ALBVISDF
		  Direct beam VIS-UV surface albedo   ALBVISDR
		  Emitted longwave at the surface   LWGEM = LWout
		  Net downward longwave flux at the surface  LWGNT = LWin-LWout, has negative values
		  Surface net downward shortwave flux  SWGNT
		  Surface incident shortwave flux      SWGDN

	  MAT1NXSLV
		  T10M  Air temp at 10m
		  T2M   Air temp at 2m
		  U10M  Eastward wind at 10m
		  V10M  Northward wind at 10m
		  U2M   eww at 2m
		  V2m   nww at 2m
  Choose netCDF format
  
  Then "Subset selected datasets"
  
  	"View subset results"
  	
  	Click on "Get list of urls"
  	
  "Save page" as an .inp file in the workd that you specified below (e.g. "filename.inp")
  
  Batch download with a FireFox plugin---see:  
  http://disc.sci.gsfc.nasa.gov/ssw/documentation/SSW_URL_List_Downloading_Instructions.html
