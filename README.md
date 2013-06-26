Info
========

This is simple local mysql password bruteforcer. It can crack either specific user or group of users/passwords. 


Author
========
op7ic (op7ica@gmail.com)


Help
========

Usage:
    To crack single password for a user:
    options: -d <dict> -u <user>
    To crack passwords for multiple users:
    options: -d <dict> -U <user dict>
   

Options:
  -h, --help            show this help message and exit
  -d FILE, --dictionary=FILE
                        local password dictionary to use
  -U FILE, --usernames=FILE
                        local username dictionary to use
  -v, --verbose         don't print any messages
  -u USERNAME, --username=USERNAME
                        username to crack password against
  -f FORCE, --force=FORCE
                        force quit after first successful crack

                        
                        
License
========
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.                        
