# Utility Scripts

Scripts I wrote to get my Mac to shout at me for:
- Drinking water every couple of hours.
- Getting out and bike around.
- Go sleep.

# Setting up cronjobs:

Clone this repository:

```
git clone https://github.com/RJ722/.scripts ~/.scripts/
```

Run:
```
crontab -e
```

and enter:

```
0 */2 * * * sh ~/.scripts/water.sh
45 17 * * * sh ~/.scripts/bike-reminder.sh
0 18 * * * sh ~/.scripts/bike.sh
0 0 * * * sh ~/.scripts/sleep.sh
15 0 * * * sh ~/.scripts/sleep-reminder-1.sh
30 0 * * * sh ~/.scripts/sleep-reminder-2.sh
```

Rise and shine!
