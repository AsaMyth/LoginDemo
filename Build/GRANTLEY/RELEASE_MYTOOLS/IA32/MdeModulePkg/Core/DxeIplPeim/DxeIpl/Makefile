#
# DO NOT EDIT
# This file is auto-generated by build utility
#
# Module Name:
#
#   Makefile
#
# Abstract:
#
#   Auto-generated makefile for building modules, libraries or platform
#
    

#
# Platform Macro Definition
#
PLATFORM_NAME = GRANTLEY
PLATFORM_GUID = A361BEE1-AEB7-4921-8505-A323899516E6
PLATFORM_VERSION = 1
PLATFORM_RELATIVE_DIR = Build
PLATFORM_DIR = $(WORKSPACE)\Build
PLATFORM_OUTPUT_DIR = Build\GRANTLEY

#
# Module Macro Definition
#
MODULE_NAME = DxeIpl
MODULE_GUID = 86D70125-BAA3-4296-A62F-602BEBBB9081
MODULE_NAME_GUID = DxeIpl
MODULE_VERSION = 1.0
MODULE_TYPE = PEIM
MODULE_FILE = DxeIpl.inf
MODULE_FILE_BASE_NAME = DxeIpl
BASE_NAME = $(MODULE_NAME)
MODULE_RELATIVE_DIR = MdeModulePkg\Core\DxeIplPeim
PACKAGE_RELATIVE_DIR = Core\DxeIplPeim
MODULE_DIR = $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim

MODULE_ENTRY_POINT = PeimInitializeDxeIpl
ARCH_ENTRY_POINT = PeimInitializeDxeIpl
IMAGE_ENTRY_POINT = _ModuleEntryPoint

INF_VERSION = 0x00010005
BASE_NAME = DxeIpl
FILE_GUID = 86D70125-BAA3-4296-A62F-602BEBBB9081
MODULE_TYPE = PEIM
VERSION_STRING = 1.0

#
# Build Configuration Macro Definition
#
ARCH = IA32
TOOLCHAIN = MYTOOLS
TOOLCHAIN_TAG = MYTOOLS
TARGET = RELEASE

#
# Build Directory Macro Definition
#
# PLATFORM_BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS
BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS
BIN_DIR = $(BUILD_DIR)\IA32
LIB_DIR = $(BIN_DIR)
MODULE_BUILD_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl
OUTPUT_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT
DEBUG_DIR = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG
DEST_DIR_OUTPUT = $(OUTPUT_DIR)
DEST_DIR_DEBUG = $(DEBUG_DIR)

#
# Shell Command Macro
#
RD = rmdir /s /q
RM = del /f /q
MD = mkdir
CP = copy /y
MV = move /y


#
# Tools definitions specific to this module
#
SYMRENAME =  echo
SYMRENAME_FLAGS = Symbol renaming not needed for

CBINDLINK_FLAGS = /nologo /NODEFAULTLIB /NOENTRY /DLL /ALIGN:16

ASLDLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe
ASLDLINK_FLAGS = /nologo /NODEFAULTLIB /ENTRY:ReferenceAcpiTable /SUBSYSTEM:EFI_BOOT_SERVICE_DRIVER

DT =  C:/Aptio_5.x_TOOLS_29/Tools/iasl5

VFR =  VfrCompile
VFR_FLAGS = -n

PP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
PP_FLAGS = /nologo /E /TC /FIAutoGen.h

LZMAF86 =  LzmaF86Compress
LZMAF86_GUID =  D42AE6BD-1352-4bfb-909A-CA72A6EAE889

GENFW =  GenFw
GENFW_FLAGS = 

DLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe
DLINK_FLAGS = /MACHINE:I386 /NOLOGO /NODEFAULTLIB /IGNORE:4001 /OPT:REF /OPT:ICF=10 /MAP /ALIGN:32 /SECTION:.xdata,D /SECTION:.pdata,D /LTCG /DLL /ENTRY:$(IMAGE_ENTRY_POINT) /SUBSYSTEM:EFI_BOOT_SERVICE_DRIVER /SAFESEH:NO /BASE:0 /DRIVER /MERGE:.data=.text /MERGE:.rdata=.text /IGNORE:4254 /PDB:$(DEBUG_DIR)/$(BASE_NAME).pdb

SLINK =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\link.exe /LIB
SLINK_FLAGS = /nologo /LTCG

ASM =  ml.exe
ASM_FLAGS = /nologo /c /WX /W3 /Cx /Zd /coff

ASL =  C:/Aptio_5.x_TOOLS_29/Tools/iasl5 #AptioV server override
ASL_FLAGS = 
ASL_OUTFLAGS =  -cr -p #AptioV server override: Flag added to skip resource descriptor checks

TIANO =  TianoCompress
TIANO_GUID =  A31280AD-481E-41B6-95E8-127F4C984779

CC =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
CC_FLAGS = /nologo /c /WX /GS- /W3 /Gs32768 /Gy /D UNICODE /GL /FIAutoGen.h /EHs-c- /GR- /GF -D PI_SPECIFICATION_VERSION=0x1001E -D EFI_SPECIFICATION_VERSION=0x20028 /wd4819 /O1ib2 -DMDEPKG_NDEBUG /D CRB_FLAG /D VFR_CRB_FLAG /D EXTERNAL_PACKAGE /D SSA_FLAG /D SSA_LOADER_FLAG /D HSX_HOST /D BDX_HOST /D LT_FLAG /DTRAD_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DME_SUPPORT_FLAG=1 /DSPS_SUPPORT=1 /DPFAT_FLAG=1 /D AMI_PAM_SAVE_RESTORE_SWSMI_VALUE=0xBE /D AMI_PAM_SAVE_CMD=0xE0 /D AMI_PAM_RESTORE_CMD=0xE1 /DUSB_PRECONDITION_ENABLE_FLAG=1 /DWDT_SUPPORT_ENABLED=1

VFRPP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
VFRPP_FLAGS = /nologo /E /TC /DVFRCOMPILE /FI$(MODULE_NAME)StrDefs.h -D PI_SPECIFICATION_VERSION=0x1001E -D EFI_SPECIFICATION_VERSION=0x20028 /wd4819 /O1ib2 -DMDEPKG_NDEBUG /D CRB_FLAG /D VFR_CRB_FLAG /D EXTERNAL_PACKAGE /D SSA_FLAG /D SSA_LOADER_FLAG /D HSX_HOST /D BDX_HOST /D LT_FLAG /DTRAD_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DPCH_SERVER_BIOS_FLAG=1 /DME_SUPPORT_FLAG=1 /DSPS_SUPPORT=1 /DPFAT_FLAG=1 /D AMI_PAM_SAVE_RESTORE_SWSMI_VALUE=0xBE /D AMI_PAM_SAVE_CMD=0xE0 /D AMI_PAM_RESTORE_CMD=0xE1 /DUSB_PRECONDITION_ENABLE_FLAG=1 /DWDT_SUPPORT_ENABLED=1

LZMA =  LzmaCompress
LZMA_GUID =  EE4E5898-3914-4259-9D6E-DC7BD79403CF

ASM16 =  ml.exe

ASLCC =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
ASLCC_FLAGS = /nologo /c /TC /FIAutoGen.h /Dmain=ReferenceAcpiTable

CBINCC_FLAGS = /nologo /c /TC /Os /FIAutoGen.h

APP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
APP_FLAGS = /nologo /E /TC

OPTROM =  EfiRom
OPTROM_FLAGS = -e

NASMB_FLAGS = -f bin

VPDTOOL =  BPDG
VPDTOOL_GUID =  8C3D856A-9BE6-468E-850A-24F7A8D38E08

ASLPP =  C:\WinDDK_7600.16385.1\WinDDk\WinDDK\7600.16385.1\bin\x86\x86\cl.exe
ASLPP_FLAGS = /nologo /EP /TC

OBJCOPY =  echo
OBJCOPY_FLAGS = objcopy not needed for

MAKE =  nmake.exe

ASMLINK =  link16.exe
ASMLINK_FLAGS = /nologo /tiny

NASM =  nasm
NASM_FLAGS = -Ox -f win32


MAKE_FILE = $(MODULE_BUILD_DIR)\Makefile

#
# Build Macro
#
OBJECT_FILES =  \
    $(OUTPUT_DIR)\DxeLoad.obj \
    $(OUTPUT_DIR)\AmiDxeIpl.obj \
    $(OUTPUT_DIR)\X64\VirtualMemory.obj \
    $(OUTPUT_DIR)\Ia32\DxeLoadFunc.obj \
    $(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj \
    $(OUTPUT_DIR)\AutoGen.obj

STATIC_LIBRARY_FILES =  \
    $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\OUTPUT\PeiServicesTablePointerLibIdt.lib \
    $(BIN_DIR)\MdePkg\Library\BaseDebugLibNull\BaseDebugLibNull\OUTPUT\BaseDebugLibNull.lib \
    $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\OUTPUT\BaseLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\OUTPUT\PeiHobLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\OUTPUT\PeiServicesLib.lib \
    $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\OUTPUT\BaseMemoryLibRepStr.lib \
    $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\OUTPUT\PeiMemoryAllocationLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\OUTPUT\PeiPcdLib.lib \
    $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\OUTPUT\BaseIoLibIntrinsic.lib \
    $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\OUTPUT\BasePciExpressLib.lib \
    $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\OUTPUT\BasePciLibPciExpress.lib \
    $(BIN_DIR)\MdePkg\Library\PeiExtractGuidedSectionLib\PeiExtractGuidedSectionLib\OUTPUT\PeiExtractGuidedSectionLib.lib \
    $(BIN_DIR)\MdeModulePkg\Library\OemHookStatusCodeLibNull\OemHookStatusCodeLibNull\OUTPUT\OemHookStatusCodeLibNull.lib \
    $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\OUTPUT\IntelIchAcpiTimerLib.lib \
    $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\OUTPUT\BasePostCodeLibPort80.lib \
    $(BIN_DIR)\IntelFrameworkModulePkg\Library\BaseUefiTianoCustomDecompressLib\BaseUefiTianoCustomDecompressLib\OUTPUT\BaseUefiTianoDecompressLib.lib \
    $(BIN_DIR)\MdeModulePkg\Library\PeiReportStatusCodeLib\PeiReportStatusCodeLib\OUTPUT\PeiReportStatusCodeLib.lib \
    $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\OUTPUT\PeimEntryPoint.lib \
    $(BIN_DIR)\MdeModulePkg\Library\DebugAgentLibNull\DebugAgentLibNull\OUTPUT\DebugAgentLibNull.lib \
    $(BIN_DIR)\MdeModulePkg\Library\PeiPerformanceLib\PeiPerformanceLib\OUTPUT\PeiPerformanceLib.lib \
    $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\OUTPUT\AmiPeiLib.lib \
    $(BIN_DIR)\IntelFrameworkModulePkg\Library\LzmaCustomDecompressLib\LzmaCustomDecompressLib\OUTPUT\LzmaDecompressLib.lib \
    $(OUTPUT_DIR)\DxeIpl.lib

INC =  \
    /I$(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\Ia32 \
    /I$(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\X64 \
    /I$(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim \
    /I$(DEBUG_DIR) \
    /I$(WORKSPACE)\MdePkg \
    /I$(WORKSPACE)\MdePkg\Include \
    /I$(WORKSPACE)\MdePkg\Include\Ia32 \
    /I$(WORKSPACE)\MdeModulePkg \
    /I$(WORKSPACE)\MdeModulePkg\Include \
    /I$(WORKSPACE)\IntelFrameworkPkg \
    /I$(WORKSPACE)\IntelFrameworkPkg\Include \
    /I$(WORKSPACE)\AmiCompatibilityPkg \
    /I$(WORKSPACE)\AmiCompatibilityPkg\Include \
    /I$(WORKSPACE)\Build \
    /I$(WORKSPACE) \
    /I$(WORKSPACE)\AmiModulePkg\Include \
    /I$(WORKSPACE)\IntelFrameworkModulePkg\Include \
    /I$(WORKSPACE)\AmiTsePkg\Include \
    /I$(WORKSPACE)\GrantleyPkg\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Chip\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Core\Include \
    /I$(WORKSPACE)\GrantleySocketPkg\Library\MemoryQpiInit\Platform\Include \
    /I$(WORKSPACE)\ServerCommonPkg\Include \
    /I$(WORKSPACE)\GrantleyPkg\Override\Restricted\IA32FamilyCpuPkg\Include \
    /I$(WORKSPACE)\AmiModulePkg

OBJECT_FILES_LIST = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\object_files.lst
STATIC_LIBRARY_FILES_LIST = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\static_library_files.lst


COMMON_DEPS = $(WORKSPACE)\MdePkg\Include\Library\ReportStatusCodeLib.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\EndOfPeiPhase.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiStatusCode.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\GraphicsOutput.h \
              $(WORKSPACE)\MdePkg\Include\Library\DebugLib.h \
              $(WORKSPACE)\MdePkg\Include\Guid\Mps.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\CpuIo.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\Decompress.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\DxeIpl.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\HiiImage.h \
              $(WORKSPACE)\MdePkg\Include\Library\IoLib.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiInternalFormRepresentation.h \
              $(WORKSPACE)\IntelFrameworkModulePkg\Include\Guid\DataHubStatusCodeRecord.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\VectorHandoffInfo.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\FirmwareVolumeInfo.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiPeiCis.h \
              $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\DxeIpl.h \
              $(WORKSPACE)\MdePkg\Include\Library\PeiServicesTablePointerLib.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\KeyboardCommonDefinitions.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareFile.h \
              $(WORKSPACE)\MdePkg\Include\Library\PcdLib.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Guid\DataHubRecords.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\StatusCodes.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiMultiPhase.h \
              $(WORKSPACE)\MdePkg\Include\Library\BaseLib.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\AmiPpi.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiDxeCis.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Ppi\PciCfg.h \
              $(WORKSPACE)\MdeModulePkg\Include\Library\S3Lib.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\AmiPeiLib.h \
              $(WORKSPACE)\MdePkg\Include\Guid\StatusCodeDataTypeId.h \
              $(WORKSPACE)\MdePkg\Include\IndustryStandard\PeImage.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiPxe.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Framework\FrameworkInternalFormRepresentation.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\DebugSupport.h \
              $(WORKSPACE)\MdePkg\Include\Guid\HiiFormMapMethodGuid.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiBootMode.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextIn.h \
              $(WORKSPACE)\MdePkg\Include\Library\PeiServicesLib.h \
              $(WORKSPACE)\MdePkg\Include\Guid\EventGroup.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\AmiStatusCodes.h \
              $(WORKSPACE)\MdePkg\Include\Guid\PcAnsi.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiBaseType.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\LoadFile.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareVolume.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\Pei.h \
              $(WORKSPACE)\MdePkg\Include\Guid\HiiPlatformSetupFormset.h \
              $(WORKSPACE)\MdePkg\Include\Library\PeimEntryPoint.h \
              $(WORKSPACE)\MdePkg\Include\PiPei.h \
              $(WORKSPACE)\MdePkg\Include\Guid\MemoryAllocationHob.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiMultiPhase.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\S3Resume2.h \
              $(WORKSPACE)\MdeModulePkg\Include\Guid\MemoryTypeInformation.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextOut.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\UefiHii.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\PciCfg2.h \
              $(WORKSPACE)\MdePkg\Include\PiDxe.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\RecoveryModule.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\DevicePath.h \
              $(WORKSPACE)\MdePkg\Include\Library\ExtractGuidedSectionLib.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiSpec.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiHob.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\HiiFont.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\HiiConfigAccess.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\Ffs.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\MasterBootMode.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\ReadOnlyVariable2.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Framework\StatusCode.h \
              $(DEBUG_DIR)\AutoGen.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiDependency.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\FormBrowser2.h \
              $(WORKSPACE)\MdePkg\Include\Guid\GlobalVariable.h \
              $(WORKSPACE)\MdeModulePkg\Include\Library\RecoveryLib.h \
              $(WORKSPACE)\MdePkg\Include\Guid\SmBios.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\SimpleTextInEx.h \
              $(WORKSPACE)\MdePkg\Include\Ia32\ProcessorBind.h \
              $(WORKSPACE)\MdePkg\Include\Guid\FirmwareFileSystem2.h \
              $(WORKSPACE)\IntelFrameworkPkg\Include\Guid\FirmwareFileSystem.h \
              $(WORKSPACE)\MdePkg\Include\Library\HobLib.h \
              $(WORKSPACE)\MdePkg\Include\Uefi\UefiGpt.h \
              $(WORKSPACE)\MdePkg\Include\Library\BaseMemoryLib.h \
              $(WORKSPACE)\MdeModulePkg\Include\Library\DebugAgentLib.h \
              $(WORKSPACE)\MdePkg\Include\Guid\SalSystemTable.h \
              $(WORKSPACE)\MdePkg\Include\Library\PerformanceLib.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\MemoryDiscovered.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\DataHubSubClass.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\Hob.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\AmiLib.h \
              $(WORKSPACE)\MdePkg\Include\Pi\PiS3BootScript.h \
              $(WORKSPACE)\MdePkg\Include\Library\UefiDecompressLib.h \
              $(WORKSPACE)\MdePkg\Include\Library\MemoryAllocationLib.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\BootInRecoveryMode.h \
              $(WORKSPACE)\MdePkg\Include\Guid\WinCertificate.h \
              $(WORKSPACE)\MdePkg\Include\Base.h \
              $(WORKSPACE)\MdePkg\Include\Guid\HiiKeyBoardLayout.h \
              $(WORKSPACE)\MdePkg\Include\Guid\Acpi.h \
              $(WORKSPACE)\AmiCompatibilityPkg\Include\Efi.h \
              $(WORKSPACE)\MdePkg\Include\Protocol\StatusCode.h \
              $(WORKSPACE)\MdePkg\Include\Ppi\GuidedSectionExtraction.h \
              

#
# Overridable Target Macro Definitions
#
FORCE_REBUILD = force_build
INIT_TARGET = init
PCH_TARGET =
BC_TARGET = 
CODA_TARGET = c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.efi \
              

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
	-@echo Building ... $(MODULE_DIR)\$(MODULE_FILE) [$(ARCH)]

dirs:
	-@if not exist $(DEBUG_DIR) $(MD) $(DEBUG_DIR)
	-@if not exist $(OUTPUT_DIR) $(MD) $(OUTPUT_DIR)


strdefs:
	-@$(CP) $(DEBUG_DIR)\AutoGen.h $(DEBUG_DIR)\$(MODULE_NAME)StrDefs.h

#
# GenLibsTarget
#
gen_libs:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseDebugLibNull\BaseDebugLibNull\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiExtractGuidedSectionLib\PeiExtractGuidedSectionLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\OemHookStatusCodeLibNull\OemHookStatusCodeLibNull\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\IntelFrameworkModulePkg\Library\BaseUefiTianoCustomDecompressLib\BaseUefiTianoCustomDecompressLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\PeiReportStatusCodeLib\PeiReportStatusCodeLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\DebugAgentLibNull\DebugAgentLibNull\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\PeiPerformanceLib\PeiPerformanceLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\IntelFrameworkModulePkg\Library\LzmaCustomDecompressLib\LzmaCustomDecompressLib\Makefile
	@cd $(MODULE_BUILD_DIR)

#
# Build Flash Device Image
#
gen_fds:
	@"$(MAKE)" $(MAKE_FLAGS) -f $(BUILD_DIR)\Makefile fds
	@cd $(MODULE_BUILD_DIR)

#
# Individual Object Build Targets
#
$(DEBUG_DIR)\DxeIpl.efi : $(DEBUG_DIR)\DxeIpl.dll
	"$(GENFW)" -e $(MODULE_TYPE) -o c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.efi c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.dll $(GENFW_FLAGS)
	$(CP) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.efi $(OUTPUT_DIR)
	$(CP) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.efi $(BIN_DIR)
	-$(CP) $(DEBUG_DIR)\*.map $(OUTPUT_DIR)
	-$(CP) $(DEBUG_DIR)\*.pdb $(OUTPUT_DIR)

$(OUTPUT_DIR)\DxeIpl.lib : $(OBJECT_FILES)
	"$(SLINK)" $(SLINK_FLAGS) /OUT:c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\DxeIpl.lib @$(OBJECT_FILES_LIST)

$(DEBUG_DIR)\DxeIpl.dll : $(MAKE_FILE)
$(DEBUG_DIR)\DxeIpl.dll : $(STATIC_LIBRARY_FILES)
	"$(DLINK)" /OUT:c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\DxeIpl.dll $(DLINK_FLAGS) $(DLINK_SPATH) @$(STATIC_LIBRARY_FILES_LIST)

$(OUTPUT_DIR)\AutoGen.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ppi\CpuIo.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiBaseType.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiMultiPhase.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareVolume.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\PeimEntryPoint.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiStatusCode.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\DebugLib.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ppi\PciCfg2.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\PiPei.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiMultiPhase.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiHob.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\IndustryStandard\PeImage.h
$(OUTPUT_DIR)\AutoGen.obj : $(DEBUG_DIR)\AutoGen.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Protocol\DebugSupport.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\BaseLib.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiPeiCis.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiDependency.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiS3BootScript.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiBootMode.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareFile.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Library\PcdLib.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Guid\WinCertificate.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Base.h
$(OUTPUT_DIR)\AutoGen.obj : $(WORKSPACE)\MdePkg\Include\Ia32\ProcessorBind.h
$(OUTPUT_DIR)\AutoGen.obj : $(DEBUG_DIR)\AutoGen.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\.\AutoGen.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\DEBUG\AutoGen.c

$(OUTPUT_DIR)\DxeLoad.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\DxeLoad.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)\DxeLoad.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\DxeLoad.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\.\DxeLoad.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\DxeLoad.c

$(OUTPUT_DIR)\AmiDxeIpl.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(WORKSPACE)\AmiModulePkg\Include\Guid\AmiGlobalVariable.h
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(WORKSPACE)\MdePkg\Include\Ppi\LoadImage.h
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(WORKSPACE)\AmiModulePkg\Include\Ppi\AmiReadyToLoadDxeCore.h
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(WORKSPACE)\AmiCompatibilityPkg\Include\AmiHobs.h
$(OUTPUT_DIR)\AmiDxeIpl.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\AmiDxeIpl.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\.\AmiDxeIpl.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\AmiDxeIpl.c

$(OUTPUT_DIR)\X64\VirtualMemory.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\X64\VirtualMemory.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)\X64\VirtualMemory.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\X64\VirtualMemory.h
$(OUTPUT_DIR)\X64\VirtualMemory.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\X64\VirtualMemory.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\X64\VirtualMemory.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\X64\VirtualMemory.c

$(OUTPUT_DIR)\Ia32\DxeLoadFunc.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\Ia32\DxeLoadFunc.obj : $(COMMON_DEPS)
$(OUTPUT_DIR)\Ia32\DxeLoadFunc.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\X64\VirtualMemory.h
$(OUTPUT_DIR)\Ia32\DxeLoadFunc.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\Ia32\DxeLoadFunc.c
	"$(CC)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\DxeLoadFunc.obj $(CC_FLAGS) -DPEI_BUILD $(INC) c:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\Ia32\DxeLoadFunc.c

$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(MAKE_FILE)
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Ppi\CpuIo.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiBaseType.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Uefi\UefiMultiPhase.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareVolume.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiStatusCode.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Ppi\PciCfg2.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\PiPei.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiMultiPhase.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiHob.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\IndustryStandard\PeImage.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiBootMode.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Protocol\DebugSupport.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Library\BaseLib.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiPeiCis.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiDependency.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiS3BootScript.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(DEBUG_DIR)\AutoGen.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Pi\PiFirmwareFile.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Library\PcdLib.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Guid\WinCertificate.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Base.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdePkg\Include\Ia32\ProcessorBind.h
$(OUTPUT_DIR)\Ia32\IdtVectorAsm.obj : $(WORKSPACE)\MdeModulePkg\Core\DxeIplPeim\Ia32\IdtVectorAsm.asm
	"$(PP)" $(PP_FLAGS) $(INC) c:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\Ia32\IdtVectorAsm.asm > c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\IdtVectorAsm.i
	Trim --source-code --convert-hex -o c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\IdtVectorAsm.iii c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\IdtVectorAsm.i
	"$(ASM)" /Foc:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\IdtVectorAsm.obj $(ASM_FLAGS) /Ic:\1218_alibaba\MdeModulePkg\Core\DxeIplPeim\Ia32 $(INC) c:\1218_alibaba\Build\GRANTLEY\RELEASE_MYTOOLS\IA32\MdeModulePkg\Core\DxeIplPeim\DxeIpl\OUTPUT\Ia32\IdtVectorAsm.iii



#
# clean all intermediate files
#
clean:
	if exist $(OUTPUT_DIR) $(RD) $(OUTPUT_DIR)
	

#
# clean all generated files
#
cleanall:
	if exist $(DEBUG_DIR) $(RD) $(DEBUG_DIR)
	if exist $(OUTPUT_DIR) $(RD) $(OUTPUT_DIR)
	$(RM) *.pdb *.idb > NUL 2>&1
	$(RM) $(BIN_DIR)\$(MODULE_NAME).efi

#
# clean all dependent libraries built
#
cleanlib:
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesTablePointerLibIdt\PeiServicesTablePointerLibIdt\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseDebugLibNull\BaseDebugLibNull\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseDebugLibNull\BaseDebugLibNull\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseLib\BaseLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiHobLib\PeiHobLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiServicesLib\PeiServicesLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseMemoryLibRepStr\BaseMemoryLibRepStr\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiMemoryAllocationLib\PeiMemoryAllocationLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiPcdLib\PeiPcdLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BaseIoLibIntrinsic\BaseIoLibIntrinsic\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciExpressLib\BasePciExpressLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePciLibPciExpress\BasePciLibPciExpress\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeiExtractGuidedSectionLib\PeiExtractGuidedSectionLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeiExtractGuidedSectionLib\PeiExtractGuidedSectionLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdeModulePkg\Library\OemHookStatusCodeLibNull\OemHookStatusCodeLibNull\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\OemHookStatusCodeLibNull\OemHookStatusCodeLibNull\Makefile cleanall
	-@if exist $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\GrantleyPkg\Library\IntelIchAcpiTimerLib\IntelIchAcpiTimerLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\BasePostCodeLibPort80\BasePostCodeLibPort80\Makefile cleanall
	-@if exist $(BIN_DIR)\IntelFrameworkModulePkg\Library\BaseUefiTianoCustomDecompressLib\BaseUefiTianoCustomDecompressLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\IntelFrameworkModulePkg\Library\BaseUefiTianoCustomDecompressLib\BaseUefiTianoCustomDecompressLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdeModulePkg\Library\PeiReportStatusCodeLib\PeiReportStatusCodeLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\PeiReportStatusCodeLib\PeiReportStatusCodeLib\Makefile cleanall
	-@if exist $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdePkg\Library\PeimEntryPoint\PeimEntryPoint\Makefile cleanall
	-@if exist $(BIN_DIR)\MdeModulePkg\Library\DebugAgentLibNull\DebugAgentLibNull\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\DebugAgentLibNull\DebugAgentLibNull\Makefile cleanall
	-@if exist $(BIN_DIR)\MdeModulePkg\Library\PeiPerformanceLib\PeiPerformanceLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\MdeModulePkg\Library\PeiPerformanceLib\PeiPerformanceLib\Makefile cleanall
	-@if exist $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\AmiCompatibilityPkg\Library\AmiPeiLib\Makefile cleanall
	-@if exist $(BIN_DIR)\IntelFrameworkModulePkg\Library\LzmaCustomDecompressLib\LzmaCustomDecompressLib\Makefile "$(MAKE)" $(MAKE_FLAGS) -f $(BIN_DIR)\IntelFrameworkModulePkg\Library\LzmaCustomDecompressLib\LzmaCustomDecompressLib\Makefile cleanall
	@cd $(MODULE_BUILD_DIR)

