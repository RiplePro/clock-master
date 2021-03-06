# Clock

This is a time tracking CLI that records your hours into a file and automate tracking hours for work, school, and other tasks.

**Why use clock?** Because using a flashy web or desktop app is distracting, and might not work without internet!

## Setup
 - with git:
```
cd /some/dir
git clone https://github.com/RiplePro/clock-master.git
# Add PATH="PATH:/some/dir/clock" to your profile/rc file.
```
 - with [mac](https://github.com/Macuyler/mac/blob/master/mac):
```
mac install https://github.com/RiplePro/clock-master.git
```

----------

## About
### Clock Logs:
```
Week 2:
  01/05/20: 0:00:00HR
  01/06/20: 3:53:00HR
  01/07/20: 4:45:00HR
  01/08/20: 1:42:00HR
  01/09/20: 3:49:00HR
  01/10/20: 2:21:00HR
  01/11/20: 1:22:00HR

  Total = 17:52:00HR
```
Clock will take care of logging how many hours you work each day, and giving you a weekly total. It will automatically take care of formatting each new week, so all you have to do is copy and paste into your invoice.

### Clock Config:
The config file is located at `~/.clock.conf`. This file is simply used to definine a custom file location for your clock log.

*Example:*
```
/home/user/Documents/work/hours.txt
```
