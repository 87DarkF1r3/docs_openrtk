
What is Aceinna Navigation Studio?
==================================

.. image:: ../media/ANSHome.png

*   The Aceinna Navigation Studio (https://developers.aceinna.com) is a navigation system developer's website and web-platform.
*   It consists of a graphical user interfSace to control and configure OpenRTK units.
*   Using a JSON configuration file ("openrtk.json"), the graphical user interface can be customized for user specific
    messaging and settings without any additional coding. This aligns the embedded code with both the Python device server
    and the GUI pages available on ANS (https://developers.aceinna.com).
*   Online tools include graphing, mapping, logging, simulation, GNSS RTK, and GNSS cloud RTK.  
*   User Forum is available at (https://forum.aceinna.com).


**Python & the Acienna Navigation Studio**

The Acienna Navigation Studio (ANS) requires Python to operate.  If the user has not installed Python, it can be installed from
https://www.python.org/downloads/.  Download and install the latest version.

An open-source Python driver for openrtk is available and required.  The Python driver can be used directly from the terminal
to load, log, and test your application. The driver leverages the PySerial library to connect to an OpenRTK of a serial connection.  The python script supports configuring units, firmware updates (JTAG is faster for debugging), and local data logging.

In addition, the open-source Python driver can acts as a server connecting the OpenRTK hardware with our ANS developer platform for a GUI experience,
cloud data storage and retrieval, as well as stored file charting/plotting tools.

The Aceinna VS Code extension ensures a python environment automatically.  The OpenRTK python code can be installed independently by cloning the repository https://github.com/Aceinna/python-openimu or using pip as shown below.

.. code-block:: bash

    pip install openimu



.. contents:: Contents
    :local: