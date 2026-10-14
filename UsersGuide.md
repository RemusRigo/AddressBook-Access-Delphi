# AddressBook-Access: User's Guide

> AddressBook-Access is **on hold**: it is an old project (2008-2009), published as found.



## Downloads & Runtimes

Download the latest release from the [Releases page](https://github.com/RemusRigo/AddressBook-Access-Delphi/releases).

|Folder|Architecture|Required Runtime|
|-|-|-|
|`Win32`|32-bit|none (native Windows app); Microsoft Jet 4.0, included in Windows|

> Use the **32-bit** build: the Jet 4.0 database driver that opens `.mdb` files exists only in 32-bit.



## Install

1. Copy `AddressBook.exe` and `Contacts.mdb` to the same folder, for example `D:\My Apps\AddressBook\`.
2. Double-click `AddressBook.exe`.



## Usage

|Action|How|
|-|-|
|**Sort** the list|Click a column header (ID, First Name, Last Name, BirthDate)|
|**New Contact**|Toolbar → **New Contact**, fill in the names and the birth date (DD, MM, YYYY), click **Ok**|
|**Edit** a contact|Double-click it, or select it and click **Edit**|
|**Alarm**|Toolbar → **Alarm**: a calendar of the current month, today highlighted, with the contacts' birthdays|

All contacts are saved in `Contacts.mdb`; you can also open it with Microsoft Access.



## Uninstall

Delete the folder (copy `Contacts.mdb` first if you want to keep your contacts).
