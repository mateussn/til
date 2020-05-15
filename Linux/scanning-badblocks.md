## Scanning Bad blocks/Bad areas on Hard Disk  

I'm suffering so much with Bad Blocks(it's a bad section on a disk drive or flash memory, so you can't read from or write to it)
right now on my HD, randomly the pc is freezing and being inutilizable.

there is a command that enables you to scan a device and find possible errors:
(this command uses badblocks program)

```sudo badblocks -v /dev/device > badsectors.txt``` 

* -v              = display operation details
* sudo            = super user permission 
* badblocks       = program used 
* /dev/device     = device you want to scan, in my case was dev/sda2
* badsectors.txt  = document with bad sectors
