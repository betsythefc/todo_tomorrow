# tomorrow
Version 0.1.0

Add-on for todo.sh to show what is due tomorrow.

## Installing

```
cd ~/.todo.actions.d
git clone git@github.com:betsythefc/tomorrow.git
```

## Usage

```
$ date
Mon Jan  8 13:35:30 PST 2018
$ todo.sh list
(A) 2018-01-04 Clean @Apartment due:2018-01-09
(B) 2018-01-04 Finish homework
$ todo.sh tomorrow
(A) 2018-01-04 Clean @Apartment due:tomorrow
```
