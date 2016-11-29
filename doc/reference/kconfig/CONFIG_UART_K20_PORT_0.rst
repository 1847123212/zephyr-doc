:orphan:

.. title:: UART_K20_PORT_0

.. option:: CONFIG_UART_K20_PORT_0:
.. _CONFIG_UART_K20_PORT_0:

This tells the driver to configure the UART port at boot, depending on
the additional configure options below.



:Symbol:           UART_K20_PORT_0
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Enable K20 UART Port 0" if UART_K20 (value: "n")
:Default values:

 *  n (value: "n")
 *   Condition: UART_K20 (value: "n")
 *  y (value: "y")
 *   Condition: (none)
 *  y (value: "y")
 *   Condition: (none)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 UART_K20 && BOARD_FRDM_K64F (value: "n")
:Locations:
 * ../drivers/serial/Kconfig.k20:12
 * ../boards/arm/hexiwear_k64/Kconfig.defconfig:43
 * ../boards/arm/frdm_k64f/Kconfig.defconfig:43