CONF_basic_minuteia = ia32/prj.conf
CONF_mint_valley    = mintvalley_prj.conf
CONF_quark_se-x86 = quark_se_prj.conf
CONF_basic_atom     = ia32/prj_expert_test.conf
CONF_galileo        = ia32_pci/prj.conf

MDEF_FILE = prj.mdef
KERNEL_TYPE = micro
PLATFORM_CONFIG ?= basic_atom
CONF_FILE = ${CONF_${PLATFORM_CONFIG}}

include ${ZEPHYR_BASE}/Makefile.inc
