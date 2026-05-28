# GPU Artifacting

GPU artifacting is caused (generally) by one of four issues:
1. Corrupt driver, or other software issue
2. GPU/motherboard misalignment
3. Failing GPU
4. Aggressive GPU overclocking

This guide covers the following:

1. Corrupt driver, or other software issue [Clean GPU Driver Re-Install](https://github.com/fosterbarnes/DocsForFriends/wiki/GPU-Artifacting#1st-potential-fix-clean-gpu-driver-re-install)

GPU/motherboard misalignment [Re-Seat GPU into MOBO](https://github.com/fosterbarnes/DocsForFriends/wiki/GPU-Artifacting#2nd-potential-fix-re-seat-gpu-into-mobo)


## Example of Issue

<td><img src="https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/1.png" alt="i1" /></td>

## 1st Potential Fix: Clean GPU Driver Re-Install

### Setup

 1. Download and install DDU  
  https://www.techpowerup.com/download/display-driver-uninstaller-ddu/
 2. Download the latest NVIDIA game ready driver (or equivalent AMD driver). Don't install this yet.   
  https://www.nvidia.com/en-us/geforce/drivers/
 3. Download and unzip NVIDA Profile inspector (or AMD equivalent)  
  https://github.com/Orbmu2k/nvidiaProfileInspector/releases/download/v3.0.1.13/nvidiaProfileInspector.zip

### Process

#### Backup NVIDIA Settings

<strong>1.</strong> Open 'nvidiaProfileInspector.exe' from your downloads, or wherever you unzipped it. 


<br>

<strong>2.</strong> Select 'Export' 
|‎|
|---|
| ![2](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/8.png) |

<br>

<strong>3.</strong> Select 'Export all customized profiles'. Save this somewhere memorable.
||
|---|
| ![3](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/9.png) |

You can close nvidiaProfileInspector when done exporting.

<br>

#### Boot into Safe Mode

<strong>1.</strong> Start holding 'Shift', then restart your computer from the start menu. Keep holding shift until you see the menu from 'Step 2'
||
|---|
| ![Step 1](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/2.png) |

<br>

<strong>2.</strong> Select 'Troubleshoot'
||
|---|
| ![Step 2](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/3.png) |

<br>

<strong>3.</strong> Select 'Advanced options' 
||
|---|
| ![Step 3](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/4.png) |

<br>

<strong>4.</strong> Select 'Startup settings' 
||
|---|
| ![Step 4](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/5.png) |

<br>

<strong>5.</strong> Select 'Restart'
||
|---|
| ![Step 5](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/6.png) |

<br>

<strong>6.</strong> Press '4' on your keyboard
||
|---|
| ![Step 6](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/7.png) |

<br>

#### Run DDU and clean GPU Drivers

<strong>1.</strong> Ignore the first-run warning. Press 'OK'


<br>

<strong>2.</strong> Press 'Close' (ignore this step if this is not your first run of DDU)
||
|---|
| ![DDU2](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/11.png) |

<br>

<strong>3.</strong> Select 'GPU' as device type
|‎|
|---|
| ![DDU2](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/12.png) |

<br>

<strong>4.</strong> Select 'Clean and restart' (Yours won't be greyed out, mine is bc I'm runnning it in a virtual machine)
||
|---|
| ![DDU2](https://raw.githubusercontent.com/fosterbarnes/DocsForFriends/main/tutorials/pic/GPUArtifacting/13.png) |

<br>

#### Re-install Drivers

Get back to regular ol' windows (no safe mode), and run the game ready NVIDIA driver that you downloaded earlier, or equivalent AMD driver. Make sure to select "Custom" when prompted, and opt for a clean install.


## 2nd Potential Fix: Re-Seat GPU into MOBO

This guide seems pretty good, this type of thing is easier to understand with a visual  

https://www.youtube.com/watch?v=PExHyGJkMG8