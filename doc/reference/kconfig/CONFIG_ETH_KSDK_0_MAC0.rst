:orphan:

.. title:: ETH_KSDK_0_MAC0

.. option:: CONFIG_ETH_KSDK_0_MAC0:
.. _CONFIG_ETH_KSDK_0_MAC0:

This is byte 0 of the MAC address.



:Symbol:           ETH_KSDK_0_MAC0
:Type:             hex
:Value:            ""
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Ranges:

 *  [0, ff]
:Prompts:

 *  "MAC Address Byte 0"
:Default values:

 *  0 (value: "n")
 *   Condition: (none)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 ETH_KSDK_0 && !ETH_KSDK_0_RANDOM_MAC && ETH_KSDK (value: "n")
:Locations:
 * ../drivers/ethernet/Kconfig.ksdk:71