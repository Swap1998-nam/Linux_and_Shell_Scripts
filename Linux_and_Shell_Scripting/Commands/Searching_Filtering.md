grep "ERROR" logfile            # search pattern
grep -r "main()" src/           # recursive search
grep -i "devops" file           # case-insensitive search
find /var/log -name "*.log"     # find log files
find . -type f -size +100M      # files > 100MB

