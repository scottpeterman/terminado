# Changelog

## 0.9.3

* Make sure SIGPIPE has default handler set [#91](https://github.com/jupyter/terminado/pull/91) ([@dlukes](https://github.com/dlukes))

## 0.9.2

* Add js files in package manifest [#87](https://github.com/jupyter/terminado/pull/87) ([@MircoT](https://github.com/MircoT))
* Add support to ppc64le [#86](https://github.com/jupyter/terminado/pull/86) ([@gururajrkatti](https://github.com/gururajrkatti))
* Fix config files for publication [#81](https://github.com/jupyter/terminado/pull/81) ([@afshin](https://github.com/afshin))

## 0.9.1

* v0.9.1 [#80](https://github.com/jupyter/terminado/pull/80) ([@afshin](https://github.com/afshin))

## 0.9.0

* Drop python 2 and 3.4 and 3.5 support [#77](https://github.com/jupyter/terminado/pull/77) ([@jasongrout](https://github.com/jasongrout))
* Make sure that all process output makes it to the terminal [#76](https://github.com/jupyter/terminado/pull/76) ([@athornton](https://github.com/athornton))

## v0.8.3

* Add kwargs to NamedTermManager.new_named_terminal [#70](https://github.com/jupyter/terminado/pull/70) ([@qntnrbns](https://github.com/qntnrbns))

## 0.8.2

* Run only the basic test on Appveyor [#64](https://github.com/jupyter/terminado/pull/64) ([@blink1073](https://github.com/blink1073))
* Fix for https://github.com/jupyter/terminado/issues/62 [#63](https://github.com/jupyter/terminado/pull/63) ([@cpranav](https://github.com/cpranav))
* Add python_requires to help pip, and version classifers [#57](https://github.com/jupyter/terminado/pull/57) ([@hugovk](https://github.com/hugovk))
* Set websocket.terminal to None when the child exits [#55](https://github.com/jupyter/terminado/pull/55) ([@takluyver](https://github.com/takluyver))

## 0.8.1

* Add support for Python 2 on Windows [#50](https://github.com/jupyter/terminado/pull/50) ([@blink1073](https://github.com/blink1073))
* Update ownership [#48](https://github.com/jupyter/terminado/pull/48) ([@blink1073](https://github.com/blink1073))

## 0.8

* Add support for Windows [#44](https://github.com/jupyter/terminado/pull/44) ([@blink1073](https://github.com/blink1073))

## 0.7

* Reduce duplication in PtyWithClients.terminate [#43](https://github.com/jupyter/terminado/pull/43) ([@srstevenson](https://github.com/srstevenson))
* Pass signal to terminal from manager method [#42](https://github.com/jupyter/terminado/pull/42) ([@srstevenson](https://github.com/srstevenson))
* Send SIGHUP to the process group in the terminal, not just the leader [#38](https://github.com/jupyter/terminado/pull/38) ([@takluyver](https://github.com/takluyver))
* Include LICENSE.txt file in the tarball [#34](https://github.com/jupyter/terminado/pull/34) ([@irushchyshyn](https://github.com/irushchyshyn))
* Add requirements and README for demos [#31](https://github.com/jupyter/terminado/pull/31) ([@stuaxo](https://github.com/stuaxo))
* Revert pinging implementation, and call super method in websocket open [#28](https://github.com/jupyter/terminado/pull/28) ([@takluyver](https://github.com/takluyver))
* keep websocket connection alive by sending pings when there is no activity [#27](https://github.com/jupyter/terminado/pull/27) ([@zyzhu2000](https://github.com/zyzhu2000))

## 0.6

* require tornado 4 [#26](https://github.com/jupyter/terminado/pull/26) ([@minrk](https://github.com/minrk))
* Close PtyProcess object instead of closing fd directly [#24](https://github.com/jupyter/terminado/pull/24) ([@takluyver](https://github.com/takluyver))
* use tornado's check_origin method name [#20](https://github.com/jupyter/terminado/pull/20) ([@minrk](https://github.com/minrk))
* Change `_log` -> `_logger`. [#19](https://github.com/jupyter/terminado/pull/19) ([@mgmarino](https://github.com/mgmarino))
* Make built wheels universal. [#14](https://github.com/jupyter/terminado/pull/14) ([@aragilar](https://github.com/aragilar))

## 0.5

* Fix bugs when max_terminals reached, with test cases [#11](https://github.com/jupyter/terminado/pull/11) ([@payne92](https://github.com/payne92))
* More liberal read time out to address Travis CI test issues [#10](https://github.com/jupyter/terminado/pull/10) ([@payne92](https://github.com/payne92))
* More unit tests [#8](https://github.com/jupyter/terminado/pull/8) ([@payne92](https://github.com/payne92))

## 0.4

* Initial unit test framework [#6](https://github.com/jupyter/terminado/pull/6) ([@payne92](https://github.com/payne92))
* Buffer the last 10 reads from the pty, and play back to new clients [#5](https://github.com/jupyter/terminado/pull/5) ([@takluyver](https://github.com/takluyver))

## 0.3.2

* add async terminate method [#3](https://github.com/jupyter/terminado/pull/3) ([@minrk](https://github.com/minrk))