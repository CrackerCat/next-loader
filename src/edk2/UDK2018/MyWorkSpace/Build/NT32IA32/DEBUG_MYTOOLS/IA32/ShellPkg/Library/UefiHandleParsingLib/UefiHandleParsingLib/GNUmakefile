#
# DO NOT EDIT
# This file is auto-generated by build utility
#
# Module Name:
#
#   GNUmakefile
#
# Abstract:
#
#   Auto-generated makefile for building modules, libraries or platform
#
    

#
# Platform Macro Definition
#
PLATFORM_NAME = NT32
PLATFORM_GUID = EB216561-961F-47EE-9EF9-CA426EF547C2
PLATFORM_VERSION = 0.4
PLATFORM_RELATIVE_DIR = Nt32Pkg
PLATFORM_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Nt32Pkg
PLATFORM_OUTPUT_DIR = Build/NT32IA32

#
# Module Macro Definition
#
MODULE_NAME = UefiHandleParsingLib
MODULE_GUID = 3CDC7177-CC2A-4678-BA8F-1A936A093FA4
MODULE_NAME_GUID = UefiHandleParsingLib
MODULE_VERSION = 1.0
MODULE_TYPE = UEFI_DRIVER
MODULE_FILE = UefiHandleParsingLib.inf
MODULE_FILE_BASE_NAME = UefiHandleParsingLib
BASE_NAME = $(MODULE_NAME)
MODULE_RELATIVE_DIR = ShellPkg/Library/UefiHandleParsingLib
PACKAGE_RELATIVE_DIR = Library/UefiHandleParsingLib
MODULE_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/ShellPkg/Library/UefiHandleParsingLib
FFS_OUTPUT_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/FV/Ffs/3CDC7177-CC2A-4678-BA8F-1A936A093FA4UefiHandleParsingLib

MODULE_ENTRY_POINT = _ModuleEntryPoint
ARCH_ENTRY_POINT = _ModuleEntryPoint
IMAGE_ENTRY_POINT = _ModuleEntryPoint

INF_VERSION = 0x00010006
BASE_NAME = UefiHandleParsingLib
FILE_GUID = 3CDC7177-CC2A-4678-BA8F-1A936A093FA4
MODULE_TYPE = UEFI_DRIVER
VERSION_STRING = 1.0

#
# Build Configuration Macro Definition
#
ARCH = IA32
TOOLCHAIN = MYTOOLS
TOOLCHAIN_TAG = MYTOOLS
TARGET = DEBUG

#
# Build Directory Macro Definition
#
# PLATFORM_BUILD_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS
BUILD_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS
BIN_DIR = $(BUILD_DIR)/IA32
LIB_DIR = $(BIN_DIR)
MODULE_BUILD_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib
OUTPUT_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT
DEBUG_DIR = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/DEBUG
DEST_DIR_OUTPUT = $(OUTPUT_DIR)
DEST_DIR_DEBUG = $(DEBUG_DIR)

#
# Shell Command Macro
#
RD = rm -r -f
RM = rm -f
MD = mkdir -p
CP = cp -f
MV = mv -f


#
# Tools definitions specific to this module
#

DTCPP = cpp

ASLDLINK = Vc\bin\link.exe
ASLDLINK_FLAGS = /NODEFAULTLIB /ENTRY:ReferenceAcpiTable /SUBSYSTEM:CONSOLE

PKCS7SIGN = Pkcs7Sign
PKCS7SIGN_GUID =  4AAFD29D-68DF-49EE-8AA9-347D375665A7



VFR = VfrCompile
VFR_FLAGS = -l -n

PP = Vc\bin\cl.exe
PP_FLAGS = /nologo /E /TC /FIAutoGen.h

LZMAF86 = LzmaF86Compress
LZMAF86_GUID =  D42AE6BD-1352-4bfb-909A-CA72A6EAE889


SYMRENAME = echo
SYMRENAME_FLAGS = Symbol renaming not needed for

GENFW = GenFw
GENFW_FLAGS = 

OPTROM = EfiRom
OPTROM_FLAGS = -e

SLINK = Vc\bin\lib.exe
SLINK_FLAGS = /nologo /LTCG



RC = \rc.exe

DTC = dtc
DTC_FLAGS = -H epapr



ASM = Vc\bin\ml.exe
ASM_FLAGS = /nologo /c /WX /W3 /coff /Cx /Zd /Zi

ASL = iasl.exe
ASL_FLAGS = 
ASL_OUTFLAGS =  -p

RSA2048SHA256SIGN = Rsa2048Sha256Sign
RSA2048SHA256SIGN_GUID =  A7717414-C616-4977-9420-844712A735BF


CC = Vc\bin\cl.exe
CC_FLAGS = /nologo /c /WX /GS- /W4 /Gs32768 /Gy /D UNICODE /O1b2 /GL /FIAutoGen.h /EHs-c- /GR- /GF /Zi /Gm

NASMB_FLAGS = -f bin

VFRPP = Vc\bin\cl.exe
VFRPP_FLAGS = /nologo /E /TC /DVFRCOMPILE /FI$(MODULE_NAME)StrDefs.h

BROTLI = BrotliCompress
BROTLI_GUID =  3D532050-5CDA-4FD0-879E-0F7F630D5AFB

CRC32 = GenCrc32
CRC32_GUID =  FC1BCDB0-7D31-49AA-936A-A4600D9DD083




LZMA = LzmaCompress
LZMA_GUID =  EE4E5898-3914-4259-9D6E-DC7BD79403CF

ASM16 = Vc\bin\ml.exe

ASLCC = Vc\bin\cl.exe
ASLCC_FLAGS = /nologo /c /FIAutoGen.h /TC /Dmain=ReferenceAcpiTable


APP = Vc\bin\cl.exe
APP_FLAGS = /nologo /E /TC


DLINK = Vc\bin\link.exe
DLINK_FLAGS = /NOLOGO /NODEFAULTLIB /IGNORE:4001 /OPT:REF /OPT:ICF=10 /MAP /ALIGN:32 /SECTION:.xdata,D /SECTION:.pdata,D /MACHINE:X86 /LTCG /DLL /ENTRY:$(IMAGE_ENTRY_POINT) /SUBSYSTEM:EFI_BOOT_SERVICE_DRIVER /SAFESEH:NO /BASE:0 /DRIVER /DEBUG /PDB:$(DEBUG_DIR)/$(BASE_NAME).pdb /EXPORT:InitializeDriver=$(IMAGE_ENTRY_POINT) /BASE:0x10000 /ALIGN:4096 /FILEALIGN:4096 /SUBSYSTEM:CONSOLE

TIANO = TianoCompress
TIANO_GUID =  A31280AD-481E-41B6-95E8-127F4C984779

VPDTOOL = BPDG
VPDTOOL_GUID =  8C3D856A-9BE6-468E-850A-24F7A8D38E08


ASLPP = Vc\bin\cl.exe
ASLPP_FLAGS = /nologo /E /C /FIAutoGen.h

OBJCOPY_ADDDEBUGFLAG =  --add-gnu-debuglink=$(DEBUG_DIR)/$(MODULE_NAME).debug
OBJCOPY = echo
OBJCOPY_FLAGS = objcopy not needed for

MAKE = Vc\bin\nmake.exe

ASMLINK = bin16\link16.exe
ASMLINK_FLAGS = /nologo /tiny

NASM = nasm
NASM_FLAGS = -Ox -f win32 -g


MAKE_FILE = $(MODULE_BUILD_DIR)/GNUmakefile

#
# Build Macro
#
OBJECT_FILES =  \
    $(OUTPUT_DIR)/UefiHandleParsingLib.obj \
    $(OUTPUT_DIR)/AutoGen.obj

INC =  \
    /I$(WORKSPACE)/ShellPkg/Library/UefiHandleParsingLib \
    /I$(DEBUG_DIR) \
    /I$(WORKSPACE)/MdePkg \
    /I$(WORKSPACE)/MdePkg/Include \
    /I$(WORKSPACE)/MdePkg/Include/Ia32 \
    /I$(WORKSPACE)/MdeModulePkg \
    /I$(WORKSPACE)/MdeModulePkg/Include \
    /I$(WORKSPACE)/ShellPkg \
    /I$(WORKSPACE)/ShellPkg/Include

OBJECT_FILES_LIST = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT/object_files.lst


COMMON_DEPS = $(WORKSPACE)/MdePkg/Include/Protocol/EdidActive.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PlatformDriverOverride.h \
              $(WORKSPACE)/ShellPkg/Include/Library/ShellLib.h \
              $(WORKSPACE)/MdePkg/Include/Library/PeCoffGetEntryPointLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverHealth.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiMultiPhase.h \
              $(WORKSPACE)/MdePkg/Include/Library/DebugLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiConfigAccess.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/AdapterInformation.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiDxeCis.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UsbHostController.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimplePointer.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DebugSupport.h \
              $(WORKSPACE)/MdePkg/Include/Guid/Gpt.h \
              $(WORKSPACE)/MdePkg/Include/Library/PcdLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextOut.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Bluetooth.h \
              $(WORKSPACE)/MdeModulePkg/Include/Library/HiiLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Tcp4.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Mbr.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ip6.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DiskIo.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiPxe.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiMultiPhase.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Tcp6.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/IpSecConfig.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ShellParameters.h \
              $(DEBUG_DIR)/AutoGen.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DevicePathToText.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextInEx.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiInternalFormRepresentation.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi50.h \
              $(DEBUG_DIR)/UefiHandleParsingLibStrDefs.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiPackageList.h \
              $(WORKSPACE)/ShellPkg/Include/Protocol/EfiShellEnvironment2.h \
              $(WORKSPACE)/MdeModulePkg/Include/Library/SortLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverConfiguration.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/FirmwareVolume2.h \
              $(WORKSPACE)/MdePkg/Include/Ia32/ProcessorBind.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ScsiPassThru.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ip4.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi10.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/LoadedImage.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/AcpiTable.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Tpm20.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Kms.h \
              $(WORKSPACE)/MdePkg/Include/Guid/FileSystemInfo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ShellDynamicCommand.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiFont.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiFirmwareFile.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/TcgService.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Pci23.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiString.h \
              $(WORKSPACE)/ShellPkg/Include/Guid/ShellLibHiiGuid.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/FirmwareManagement.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PlatformToDriverConfiguration.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/VlanConfig.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Usb.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DevicePathUtilities.h \
              $(WORKSPACE)/MdePkg/Include/Guid/HiiPlatformSetupFormset.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiFirmwareVolume.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi51.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiGpt.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/BlockIo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextIn.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/PciCodeId.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/PciExpress30.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimpleFileSystem.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ComponentName2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/IScsiInitiatorName.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi60.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/AbsolutePointer.h \
              $(WORKSPACE)/MdePkg/Include/Guid/FileInfo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UgaDraw.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ip4Config2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/LoadFile.h \
              $(WORKSPACE)/MdePkg/Include/Library/UefiBootServicesTableLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SimpleNetwork.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Pci22.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Udp6.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/PeImage.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi20.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/AcpiAml.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UserCredential2.h \
              $(WORKSPACE)/ShellPkg/Include/Library/ShellCommandLib.h \
              $(WORKSPACE)/MdePkg/Include/Uefi.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiDatabase.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/EdidOverride.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/NetworkInterfaceIdentifier.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/BlockIo2.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/UefiTcgPlatform.h \
              $(WORKSPACE)/MdePkg/Include/Library/PrintLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Usb2HostController.h \
              $(WORKSPACE)/MdePkg/Include/Guid/GlobalVariable.h \
              $(WORKSPACE)/ShellPkg/Include/Protocol/EfiShellInterface.h \
              $(WORKSPACE)/MdeModulePkg/Include/Guid/ConsoleOutDevice.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DiskIo2.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi30.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Shell.h \
              $(WORKSPACE)/MdePkg/Include/PiDxe.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiHob.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/LoadFile2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UnicodeCollation.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Mtftp6.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/TapeIo.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiS3BootScript.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UgaIo.h \
              $(WORKSPACE)/MdeModulePkg/Include/Guid/StandardErrorDevice.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi40.h \
              $(WORKSPACE)/MdePkg/Include/Guid/WinCertificate.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PxeBaseCode.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UserCredential.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Mtftp4.h \
              $(WORKSPACE)/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/BusSpecificDriverOverride.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DebugPort.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/IdeControllerInit.h \
              $(WORKSPACE)/MdePkg/Include/Library/UefiLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UserManager.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DevicePath.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DeviceIo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DiskInfo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ip6Config.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/SerialIo.h \
              $(WORKSPACE)/MdePkg/Include/Base.h \
              $(WORKSPACE)/MdePkg/Include/Library/MemoryAllocationLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Udp4.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/GraphicsOutput.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ebc.h \
              $(WORKSPACE)/MdePkg/Include/Guid/HiiFormMapMethodGuid.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DevicePathFromText.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiStatusCode.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverDiagnostics2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ip4Config.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Bis.h \
              $(WORKSPACE)/MdePkg/Include/Library/BaseLib.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Pci.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ScsiPassThruExt.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ManagedNetwork.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverDiagnostics.h \
              $(WORKSPACE)/ShellPkg/Include/Library/HandleParsingLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Dhcp6.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Eap.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Pcd.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Pci30.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverBinding.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiBaseType.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiBootMode.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverSupportedEfiVersion.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Dhcp4.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverConfiguration2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/IpSec.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/PciExpress21.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PciIo.h \
              $(WORKSPACE)/MdePkg/Include/Library/BaseMemoryLib.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ComponentName.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/FormBrowser2.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/EapManagement.h \
              $(WORKSPACE)/MdePkg/Include/Uefi/UefiSpec.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Arp.h \
              $(WORKSPACE)/MdeModulePkg/Include/Guid/ConsoleInDevice.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Ftp4.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiImage.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Decompress.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/EdidDiscovered.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/AtaPassThru.h \
              $(WORKSPACE)/MdePkg/Include/Pi/PiDependency.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PciRootBridgeIo.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Atapi.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/AuthenticationInfo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/UsbIo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PxeBaseCodeCallBack.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/HiiConfigRouting.h \
              $(WORKSPACE)/MdePkg/Include/Guid/PcAnsi.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DriverFamilyOverride.h \
              $(WORKSPACE)/MdePkg/Include/Library/DevicePathLib.h \
              $(WORKSPACE)/MdePkg/Include/IndustryStandard/Tpm12.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/ScsiIo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/Hash.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/PartitionInfo.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/DeferredImageLoad.h \
              $(WORKSPACE)/MdePkg/Include/Protocol/StorageSecurityCommand.h \
              

#
# Overridable Target Macro Definitions
#
FORCE_REBUILD = force_build
INIT_TARGET = init
PCH_TARGET =
BC_TARGET = 
CODA_TARGET = /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT/UefiHandleParsingLib.lib \
              

#
# Default target, which will build dependent libraries in addition to source files
#

all: mbuild


#
# Target used when called from platform makefile, which will bypass the build of dependent libraries
#

pbuild: $(INIT_TARGET) $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# ModuleTarget
#

mbuild: $(INIT_TARGET) $(BC_TARGET) gen_libs $(PCH_TARGET) $(CODA_TARGET)

#
# Build Target used in multi-thread build mode, which will bypass the init and gen_libs targets
#

tbuild: $(BC_TARGET) $(PCH_TARGET) $(CODA_TARGET)

#
# Phony target which is used to force executing commands for a target
#
force_build:
	-@

#
# Target to update the FD
#

fds: mbuild gen_fds

#
# Initialization target: print build information and create necessary directories
#
init: info dirs

info:
	-@echo Building ... $(MODULE_DIR)/$(MODULE_FILE) [$(ARCH)]

dirs:
	-@$(MD) $(DEBUG_DIR)
	-@$(MD) $(OUTPUT_DIR)


strdefs:
	-@$(CP) $(DEBUG_DIR)/AutoGen.h $(DEBUG_DIR)/$(MODULE_NAME)StrDefs.h

#
# GenLibsTarget
#
gen_libs:
	@cd $(MODULE_BUILD_DIR)

#
# Build Flash Device Image
#
gen_fds:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BUILD_DIR)/GNUmakefile fds
	@cd $(MODULE_BUILD_DIR)

#
# Individual Object Build Targets
#
$(OUTPUT_DIR)/UefiHandleParsingLib.lib : $(OBJECT_FILES)
$(OUTPUT_DIR)/UefiHandleParsingLib.lib : $(OBJECT_FILES_LIST)
	"$(SLINK)" $(SLINK_FLAGS) /OUT:/Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT/UefiHandleParsingLib.lib @$(OBJECT_FILES_LIST)

$(OUTPUT_DIR)/AutoGen.obj : $(MAKE_FILE)
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi10.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/AcpiAml.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Guid/HiiFormMapMethodGuid.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Library/PcdLib.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextOut.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Bluetooth.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiPxe.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi30.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiMultiPhase.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiBaseType.h
$(OUTPUT_DIR)/AutoGen.obj : $(DEBUG_DIR)/AutoGen.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextInEx.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiSpec.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi51.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiGpt.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Uefi/UefiInternalFormRepresentation.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Protocol/SimpleTextIn.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi50.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi40.h
$(OUTPUT_DIR)/AutoGen.obj : $(DEBUG_DIR)/UefiHandleParsingLibStrDefs.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Guid/WinCertificate.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi60.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Protocol/DevicePath.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Guid/PcAnsi.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Base.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/Ia32/ProcessorBind.h
$(OUTPUT_DIR)/AutoGen.obj : $(WORKSPACE)/MdePkg/Include/IndustryStandard/Acpi20.h
$(OUTPUT_DIR)/AutoGen.obj : $(DEBUG_DIR)/AutoGen.c
	"$(CC)" /Fo/Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT/./AutoGen.obj $(CC_FLAGS) $(INC) /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/DEBUG/AutoGen.c

$(OUTPUT_DIR)/UefiHandleParsingLib.obj : $(MAKE_FILE)
$(OUTPUT_DIR)/UefiHandleParsingLib.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)/UefiHandleParsingLib.obj : $(WORKSPACE)/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib.c
	"$(CC)" /Fo/Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/Build/NT32IA32/DEBUG_MYTOOLS/IA32/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib/OUTPUT/./UefiHandleParsingLib.obj $(CC_FLAGS) $(INC) /Users/g5/Documents/GitHub/next-loader/src/edk2/UDK2018/MyWorkSpace/ShellPkg/Library/UefiHandleParsingLib/UefiHandleParsingLib.c



#
# clean all intermediate files
#
clean:
	$(RD) $(OUTPUT_DIR)
		$(RM) AutoGenTimeStamp

#
# clean all generated files
#
cleanall:
	$(RD) $(DEBUG_DIR)
	$(RD) $(OUTPUT_DIR)
	$(RM) *.pdb *.idb > NUL 2>&1
	$(RM) $(BIN_DIR)/$(MODULE_NAME).efi
	$(RM) AutoGenTimeStamp

#
# clean all dependent libraries built
#
cleanlib:
	@cd $(MODULE_BUILD_DIR)

