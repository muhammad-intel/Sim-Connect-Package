# Sim-Connect-Package
Simics cosim CXL connect software package

The purpose is to connect the SIMICS simulator to co-simualtion environment where a CXL device is being simulated and responds to PCIe/CXL requests and send back response.
Bios can enumerate the simulated device , enumeration process follows a set of configuration read/write and device memory access operation.
and a relay mechanism , we call it CXL RELAY is developed to transfer these requests and replies between the host side SIMICS simulator and the device under development in the cosim environment. 
The Source directory structure 
    Sim-Connect-Package
        ->cxl_relay
        ->install_base86_qsp_124
        ->applications.simulators.simics.contrib.contrib
        
 Important batch files that controls the package behavior
          bios.csh
          client.csh
          server.csh
          simulate.csh
          source.me
          testhost.csh
 
        
