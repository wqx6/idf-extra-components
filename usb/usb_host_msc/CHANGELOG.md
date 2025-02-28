## 1.0.0

- Initial version

## 1.0.1

- Fix compatibility with IDF v4.4

## 1.0.2

- Increase transfer timeout to 5 seconds to handle slower flash disks

## 1.0.4

- Claim support for USB composite devices

## 1.1.0

- Significantly increase performance with Virtual File System by allowing longer transfers
- Optimize used heap memory by reusing the Virtual File System buffer
- Optimize CPU usage by putting the background MSC task to 'Blocked' state indefinitely when there is nothing to do
- Fix MSC commands for devices on interface numbers other than zero
- Replace unsafe debug functions for direct access of MSC sectors with private SCSI commands
