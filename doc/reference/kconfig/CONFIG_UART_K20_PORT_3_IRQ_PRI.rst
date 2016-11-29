:orphan:

.. title:: UART_K20_PORT_3_IRQ_PRI

.. option:: CONFIG_UART_K20_PORT_3_IRQ_PRI:
.. _CONFIG_UART_K20_PORT_3_IRQ_PRI:

The interrupt priority for UART port.



:Symbol:           UART_K20_PORT_3_IRQ_PRI
:Type:             int
:Value:            ""
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Port 3 Interrupt Priority" if UART_K20_PORT_3 (value: "n")
:Default values:

 *  0 (value: "n")
 *   Condition: UART_K20_PORT_3 (value: "n")
 *  3 (value: "n")
 *   Condition: (none)
 *  3 (value: "n")
 *   Condition: (none)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 UART_K20 && BOARD_FRDM_K64F && UART_K20_PORT_3 (value: "n")
:Locations:
 * ../drivers/serial/Kconfig.k20:130
 * ../boards/arm/hexiwear_k64/Kconfig.defconfig:73
 * ../boards/arm/frdm_k64f/Kconfig.defconfig:73