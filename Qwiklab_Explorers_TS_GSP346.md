# Prepare Data for Looker Dashboards and Reports: Challenge Lab || [GSP346](https://www.cloudskillsboost.google/games/5429/labs/35216) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

## Copy and paste below code in Looker

TASK 1 :-
```
explore: +airports {
     query: start_from_here{
      dimensions: [city, state]
      measures: [count]
      filters: [airports.facility_type: "HELIPORT^ ^ ^ ^ ^ ^ ^ "]
    } 
}
```

### Follow next steps for Task-1 Carefully

TASK 2 :-
```
explore: +airports {
    query: start_from_here{
      dimensions: [facility_type, state]
      measures: [count]
    }
  }
```

### Follow next steps for Task-2 Carefully

TASK 3 :-
```
explore: +flights {
    query: start_from_here{
      dimensions: [aircraft_origin.city, aircraft_origin.state]
      measures: [cancelled_count, count]
    }
}
```

### Follow next steps for Task-3 Carefully


# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)
