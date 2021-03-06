cdt-proc
========

Eclipse CDT extension for Oracle Pro*C

Screenshot
----------

![Preview](https://github.com/buntatsu/cdt-proc/blob/master/proc.png)

Installation
------------
1. Install Eclipse CDT.

   http://www.eclipse.org/cdt/

2. Download the zip file from https://github.com/buntatsu/cdt-proc/releases.

3. Unzip the file.

4. Backup CDT core files in Eclipse plugin folder.

    For example,

        org.eclipse.cdt.core_6.0.0.201606062011.jar
        org.eclipse.cdt.core.source_6.0.0.201606062011.jar

5. Copy the unzipped files into Eclipse plugin folder.

    For example,

		eclipse
		|-- dropins
		|   |-- buntatsun.cdt.proc.ui_3.4.0.jar
		|   `-- buntatsun.cdt.proc_3.4.0.jar
		|-- plugins
		    |    :
		    |-- org.eclipse.cdt.core_6.0.0.201606062011.jar         (overwrite)
		    |-- org.eclipse.cdt.core.source_6.0.0.201606062011.jar  (overwrite)
		         :

6. Restart Eclipse.

