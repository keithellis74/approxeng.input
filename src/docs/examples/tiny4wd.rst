.. _example_tiny4wd:

Tiny4WD Robot Drive
===================

Tiny4WD is a great first robot kit designed by Brian Corteil (`\@CannonFodder <https://twitter.com/cannonfodder>`__ and
`\@CoretecRobotics <https://twitter.com/coretecrobotics>`__). You can buy the kits from the lovely, if money-sucking,
pirates at `\@pimoroni <https://twitter.com/pimoroni>`__ from
`their online shop <https://shop.pimoroni.com/products/coretec-tiny-4wd-robot-rover>`__. The code below shows, with a
few extra bits and pieces needed in case you're running without the robot libraries, how to use this library to drive
it around. The left analogue stick controls the robot, and the HOME button exits.

.. image:: tiny4wd.jpg

.. literalinclude:: ../../../scripts/tiny4wd_drive.py
    :language: python
    :linenos:
