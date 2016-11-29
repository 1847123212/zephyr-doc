:orphan:

.. title:: TI_CC2520_SPI_FREQ

.. option:: CONFIG_TI_CC2520_SPI_FREQ:
.. _CONFIG_TI_CC2520_SPI_FREQ:

This option sets the SPI controller's frequency. Beware this value
depends on the SPI controller being used and also on the system
clock.



:Symbol:           TI_CC2520_SPI_FREQ
:Type:             int
:Value:            ""
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "SPI system frequency"
:Default values:

 *  0 (value: "n")
 *   Condition: (none)
 *  4 (value: "n")
 *   Condition: (none)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 NETWORKING_WITH_15_4_TI_CC2520 && BOARD_QUARK_SE_C1000_DEVBOARD (value: "n")
:Locations:
 * ../drivers/ieee802154/Kconfig:73
 * ../boards/x86/quark_se_c1000_devboard/Kconfig.defconfig:58