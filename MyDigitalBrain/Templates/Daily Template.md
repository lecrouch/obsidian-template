---
date: {{date}}
type: daily
---

# TOP LEVEL 
---
---
---

## Objectives
#### personal
[[2022 Personal Objectives]]
```tasks
path includes 2022 Personal Objectives
heading includes Q2
```

#### Work
[[2022 Work Objectives]]
```tasks
path includes 2022 Work Objectives
heading includes Q2
```


# DAY - BEGINNING
---
---

## Morning Check List
- [ ] Write *[[{{date}}#Schedule]]*
- [ ] Review *[[{{date}}#Deadlines]]*
- [ ] Review *[[{{date}}#Tasks]]*
- [ ] Update and pick *[[{{date}}#Daily Focus]]* Items

---
---

## Daily Focus

### *What are the most important things that I need to do today?*
##### limit 3 each
#### Personal
- [ ] 


#### Work
- [ ] 

---
---

## Schedule
#### **yesterday:** [[Day Planner-<% tp.date.now("YYYYMMDD", -1) %>]] 
#### **today:** [[Day Planner-<% tp.date.now("YYYYMMDD") %>]] 

---
---
---

# DAY - DURING
---
---
---

## Deadlines
```tasks
not done
path includes Tasks
due after 2022-01-01
sort by due
sort by priority
```

---
---

## Followups
#### personal:
[[Personal Followups]]
```tasks
not done
path includes Personal Followups
sort by priority
```

#### Work:
[[Work Followups]]
##### limit 5
```tasks
not done
path includes Work Followups
sort by priority
limit 5
```

---
---

## Tasks
#### personal 
##### [[2022 Personal Tasks]]
##### limit 5
```tasks
not done
path includes 2022 Personal Tasks
sort by due
sort by priority
limit 5
```


#### Work  
##### [[2022 Work Tasks]]
##### limit 5
```tasks
not done
path includes 2022 Work
path does not include Objectives
sort by due
sort by priority
limit 5
```

---
---
---

# DAY -  END
---
---
---

## Reflection
## *Personal:*
#### what did I accomplish
- derp #wins

#### what am I grateful for
- derp #gratitude 

#### Challenges
- derp #challenges 


## *Work:*
#### what did I accomplish
- derp #wins

#### what am I grateful for
- derp #gratitude

#### challenges
- derp #challenges 

--- 
---

## Habit Tracker
🏋️  :  Exercise
🚀  :  Space Travel
🎶  :  Listen to some sounds
⚙️   :  Gears?
👫  :  Relationship Fertilizer
🤠  :  Act like a cowperson

#### Today's Habits:  [[Habits <% tp.date.now("YYYYMMDD") %>]] 
##### Nailed: 🟢     Failed: 🔴      Not Recorded: ⚪️
```dataview
TABLE date as Date, 🏋️, 🚀, 🎶, ⚙️, 👫, 🤠
FROM "Daily Habits"
SORT date DESC
LIMIT 15
```
