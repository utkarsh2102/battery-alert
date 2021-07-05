# Battery-Alert

Battery Alert is a shell script that is written to notify the user about the current battery status so that they never run out of charging.

With this script, the user neither has to worry about leaving the device on charge nor while they are working.

The script will notify you to **Put-On Charging** when the battery is low and **Remove Charging** when the system is done charging.


## Installation
Setup for [battery-alert](https://github.com/utkarsh2102/battery-alert)



```bash
# Clone the Repository
$ git clone https://github.com/utkarsh2102/battery-alert.git

# To run this script for every 15 minutes(can be modified), add a cron job
$ crontab -e
# add following into the editor
*/15 * * * * <path-to-script>
```

## How it looks?
```
</IMAGE>
```

## Contributing
If you have found a bug or an issue, please feel free to create a Pull Request.
If you want to add a new feature to the script, open an issue along with the relevant description of the feature.

## License
The script is licensed under [MIT](https://github.com/utkarsh2102/battery-alert/blob/master/LICENSE) section.


##
Copyright © 2020 Utkarsh Gupta
