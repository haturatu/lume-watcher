# lume-watcher

## Usage

1. Clone this repository.
```
git clone https://github.com/haturatu/lume-watcher
```

2. Move the lume-watcher script to /etc/init.d/lume-watcher.
```
sudo mv lume-watcher /etc/init.d/lume-watcher
```

3. Optionally, change the permissions of the lume-watcher script.
```
sudo chmod +x /etc/init.d/lume-watcher
```

4. Add a service to SysVinit.
```
sudo update-rc.d lume-watcher defaults
```
done!

## Start-Stop
```
sudo /etc/init.d/lume-watcher start
```
```
sudo /etc/init.d/lume-watcher stop
```
```
sudo /etc/init.d/lume-watcher restart
```
```
sudo /etc/init.d/lume-watcher status
```
