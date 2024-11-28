# pytest-porcochu

Like `pytest-pikachu` but it's a pikachuified pig.

`pytest-porcochu` prints ascii art of Surprised Porco when all tests pass.

## Installation

```
$ pip install pytest-porcochu
```

## Usage

Pass the `--porcochu` option to `pytest` as a command line flag or configuration
file option to get these stunning effects.

```
$ pytest --porcochu
============================= test session starts ==============================
platform linux -- Python 3.9.6, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: /home/.../pytest-porcochu, configfile: tox.ini, testpaths: tests
plugins: porcochu-0.1.0
collected 4 items

tests/test_plugin.py ....                                                [100%]

============================== 4 passed in 0.11s ===============================

%%%%@%%%%%%%%%@%%%%%%%#########%%%#%%######################%@%%##*+===---=-::::
%%%%@%%%@%%%%%@%%%%########################################%@%###*+==-::-=-.:::
@@%@@%%%@@%%%%@@%%%######%##########%################*###**#@%*=--==--::--:::-:
%%@%%%%%@%#----::::-=**#####%%%%%#%%##################*+:----==---==---:--:..::
%%@%%%%%%%%=--=========-:+##%%%############*#######+:--=======---+=---::-:. .::
%@@%%%%%%%%%=---==========:.+#%%###############*=:.:-=======----=+=---::-:. .::
%@@%%%%%%%%%*------==+++++=:...-=+=:.    .:--:...::-======--::::+==---::-:. .::
%%%%%%%%%%%%%-:::::--==+++==-.                  .::-===----:-::-+=---:::--:..::
@@%@%%%%@@@@%*-:-::--==+==++-.                   .-===----:::::++==---::--:.:-:
@@@@@@@@@@@@%%+--:::---===+=:..                  .-=--=-:::::-+++===--===++=+**
@@@@@@@@@@@@%@%*--:::::--:--::::...           ....::::::::::=#%#%%####%%%%%%%%%
@@@@@@@@@@@@+==+%+----:::::--::-=::...       ..#::--:::::-=*%%%%%%%%%%%%%%%%%%%
@@@@@@@@@%-:===#%%%*=--::-=:-.:-:::.....     .:...-#*---*#@@@@@@@@@@@@@@@@@@@@@
------=+=::-==+#%@@%%#++++:--.:::....:..       ...:-@%##%@@@@@@@@@@@@#*%@@@@@@@
-:::-==---=+===#@%%%%%%%#:--:.:::....:...   .   ...:=%%%%%%%%%%%%%%%%%#%%%%%%%%
:::::---===++==#@@@@@%%%:---::::.....:..::::.  ....::%%%%%%%%%%%%%%%%%%%%%%%%%%
:::::--:-=++==+%@@@@@@%%:--::::::::.:.:--:::-:...:.::##%%%%%%%%%%%%%%%%%%%%%%%%
::::--:-+*+#*+#%%@@@@@@--::::::::::::=+#----#+-:.:.::-###%%%%%%%%%%%%@%@@@%%%%%
-:::---=*%*%@@%%@@@@@@%--:::::::-:--=-:-====-:::::::::%%%###%%%%%%%%%##%%%@@@@%
=-::--=++**%@@@@@@@@@@*--::::--------==+++++==-:::::::#@%@@%%%%#***********##%#
:-::--=+++*%@@@@@@@@@@*-----::--------=+====---:::::::=@@@@@%%#****************
::-:::==+*#@@@@@@@@@@@=---------=====----------::--::::%@@@@%******************
---:---=+*%@@@@@@@@@@@#----=+========+========++=--:::-+@@@%#******#***********
----:--=+*%@@@@@@@@@@@@---:-=*#+++==+====++*#*=-:::::---%@@%#*******#**********
==--+++++*#@@@@@@@@@@@@#--::--+##*+++=++****+=-:::::-=--=@@##******#***********
#++++==++**%@@%%%%@@@@@=--::::-+*##********==-:::::--==--#@%#**++**************
===+++****+==-------:---=--::::-***+******+=---::::=+++++==+==========+********
++++****+++++====++=++====-:::::+*+++=++++=-----:-+++==+==-----=-------====----

```

## Prior art

I wrote this `pytest` plugin after seeing [this Reddit thread][1]. I used the
answer in [this Stack Overflow question][2] on how to pass information between
different `pytest` hooks.

## License

Distributed under the terms of the MIT license, `pytest-porcochu` is free and
open source software.

[1]:
  https://www.reddit.com/r/ProgrammerHumor/comments/a381ur/the_correct_reaction_to_unit_tests_passing/
[2]: https://stackoverflow.com/a/53640991
