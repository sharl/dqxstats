# NAME

dqxstats - display character's level if change

# SYNOPSIS

## entry

if your character's page is http://hiroba.dqx.jp/sc/character/nnnnnnnnn/ , specify `nnnnnnnnn` to entry your character.

```
$ dqxstats nnnnnnnnn
```

note: character's page must be opened for everyone. see also http://dqxstat.info/dqx/

## display

### show changes

```
$ dqxstats
```

if job level has changed, display like following:

```
おかんの魔法使いのレベルが80になった！
おかんの道具鍛冶職人のレベルが40になった！
おかんの道具鍛冶職人の評判がＳ級世界屈指になった！
おかんの釣りのレベルが10になった！
```

if skill effect has changed, display like following:

```
おかんのさいだいＨＰが常時+140になった！
おかんのちからが常時+50になった！
おかんのすばやさが常時+220になった！
```

### show current status


```
$ dqxstats -p
```

display list of the current status like following:

```
おかん         道具鍛冶職人 40 Ｓ級世界屈指
|戦|僧|魔|武|盗|旅|バ|パ|魔|レ|賢|ス|ま|ど|
|士|侶|使|闘|賊|芸|ト|ラ|戦|ン|者|パ|も|う|
|80|80|80|80|80|80|80|80|80|80|80|80|80|80|
```

note: status is the level at detected.

## file

names and levels are recording to `~/.dqxstats`.


enjoy.
