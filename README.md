# AMBA_APB_SRAM
AMBA v.3 APB v.1 Specification Complaint Slave SRAM Core design and testbench. The testbench is developed using System Verilog and UVM and can be used as standalone Verification IP (VIP). 

# Project Structure
This project is organized in following manner


<ui>![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) AMBA_APB_SRAM  
  &nbsp;&nbsp;|   
  &nbsp;&nbsp;|->&nbsp;&nbsp;![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) doc : contains project documents like testcase plan, verification plan etc. <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) TestcasePlan     
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|-> ![Excel File](http://icons.iconarchive.com/icons/carlosjj/microsoft-office-2013/16/Excel-icon.png) apb_sram_testplan.xlsx  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) VerificationPlan  
&nbsp;&nbsp;|->&nbsp;&nbsp;![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) rtl : contains rtl code of APB SRAM Core.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![Verilog File](http://icons.iconarchive.com/icons/untergunter/leaf-mimes/16/text-x-generic-icon.png) apb_v3_sram.v  
&nbsp;&nbsp;|->&nbsp;&nbsp;![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) scripts : contains scripts for running tests.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![shell script](http://icons.iconarchive.com/icons/guillendesign/variations-2/16/Script-Console-icon.png) runscript.ps1 : script for ruuning tests with Questasim or modelsim on windows <br/>
&nbsp;&nbsp;|->&nbsp;&nbsp;![FolderIcon](http://icons.iconarchive.com/icons/paomedia/small-n-flat/16/folder-icon.png) sim : contains simulation work directory. This is where you should open a terminal to run your tests.<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![Text File](http://icons.iconarchive.com/icons/untergunter/leaf-mimes/16/text-x-generic-icon.png)tb_filelist.f: main file list<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|->![Text File](http://icons.iconarchive.com/icons/untergunter/leaf-mimes/16/text-x-generic-icon.png)tb_filelist_for_VRM.f : Filelist for running regression tests with Questa Verification Run Manager (VRM). You should modify this file with absolute path of your working directory   
