##vm-sorry this application cannot run under a virtual machine
  
  vmx记事本末尾加上：
  
  isolation.tools.getPtrLocation.disable = "TRUE"
  
  isolation.tools.setPtrLocation.disable = "TRUE"
  
  isolation.tools.setVersion.disable = "TRUE"
  
  isolation.tools.getVersion.disable = "TRUE"
  
  monitor_control.disable_directexec = "TRUE"
  
  monitor_control.disable_chksimd = "TRUE"
  
  monitor_control.disable_ntreloc = "TRUE"
  
  monitor_control.disable_selfmod = "TRUE"
  
  monitor_control.disable_reloc = "TRUE"
  
  monitor_control.disable_btinout = "TRUE"
  
  monitor_control.disable_btmemspace = "TRUE"
  
  monitor_control.disable_btpriv = "TRUE"
  
  monitor_control.disable_btseg = "TRUE" 
