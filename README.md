
## Submit data to the public databases
- Log into NCBI portal https://submit.ncbi.nlm.nih.gov/subs/sra/
- Click ´New submission´
- Ensure contact information is correct
- Press continue
- Fill in the page 
  - Use an existing bioproject ID or create a new one
  - Did you already register the sample?
  - Select publication date
  - Press continue
- If you did not already register a project
  - Provide Project title
  - Public description
  - Select relevance
  - Press continue
- If you did not already register the samples
  - Select "Metagenome or environmental"
  - Press continue
  - Fill in the required fields: sample_name, organism, host, collection_date, 	geo_loc_name, 	lat_lon
  - Press continue
 - Download and fill out SRA metadata sheet
  - Upload sheet
  - Press continue
- Select "FTP or Aspera Command Line file preload"
  - Get the aspera key onto your follder on the server
  - Edit the paths in the command example provided on the NCBI page
  - open a screen session on the server e.g. "screen -S NCBIupload"
  - Load the Aspera module on the server "module load Aspera-CLI"
  - Enter the upload command 
  - Check that the upload starts as expected (We should have a bit less than 100 MB/s)
  - Detach from the screen session
  - Periodically check the upload progress
  - Select the data from the preload area
  - Press continue
- Press finish
