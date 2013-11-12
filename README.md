Railscast sm-rc164
==================
cron Job
```
cron is used when schdule jobs are recurring
```
git clone
```
git clone https://github.com/sweetymehta/sm-rc164.git
```
Gem file
```
gem 'whenever'
bundlle install
```
Go to terminal
```
wheneverize
and then you will have config/schedule.rb file
```
Now write cron jobs there
```
every :sunday , :at => '4:20 am' do
  command "rm something"
end
```
Terminal to see all jobs
```
whenever
```


