### The bcdedit command is used to manage the boot configuration data (BCD) in Windows. The BCD stores boot-time configuration data, such as boot options and boot manager settings. Here are some of the most commonly used bcdedit commands and their functions:

- "bcdedit /enum" - This command displays the current boot configuration data in the Command Prompt window. It lists all the available boot loader entries, the current boot loader settings, and the default boot loader settings.

-  "bcdedit /set" - This command sets the value of a specified boot loader setting. You can use this command to modify the boot configuration data. For example, you can use this command to set the default operating system or to modify the boot options.

-  "bcdedit /copy" - This command creates a copy of an existing boot loader entry. You can use this command to create a new boot loader entry based on an existing one.

-  "bcdedit /delete" - This command deletes an existing boot loader entry. You can use this command to remove an old or unwanted boot loader entry.

  -  "bcdedit /default" - This command sets the default boot loader entry. You can use this command to specify which operating system or boot loader entry should be loaded by default.

-  Here are five examples of how you can use the bcdedit command:

-  To display the current boot configuration data, type "bcdedit /enum" in the Command Prompt window and press Enter.

-  To set the default operating system to Windows 10, type "bcdedit /default {current}" in the Command Prompt window and press Enter.

-  To create a new boot loader entry based on an existing one, type "bcdedit /copy {current} /d "New Entry"" in the Command Prompt window and press Enter. This will create a new boot loader entry with the name "New Entry".
-  To delete an existing boot loader entry, type "bcdedit /delete {identifier}" in the Command Prompt window and press Enter. Replace {identifier} with the identifier of the boot loader entry you want to delete.
-  To modify the boot options for a specific boot loader entry, type "bcdedit /set {identifier} options {value}" in the Command Prompt window and press Enter. Replace {identifier} with the identifier of the boot loader entry you want to modify, and replace {value} with the new boot options you want to set.
