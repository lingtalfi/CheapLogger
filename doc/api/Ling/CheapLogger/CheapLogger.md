[Back to the Ling/CheapLogger api](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger.md)



The CheapLogger class
================
2019-12-19 --> 2021-05-31






Introduction
============

The CheapLogger class.



Class synopsis
==============


class <span class="pl-k">CheapLogger</span>  {

- Properties
    - private static string [$path](#property-path) = /tmp/CheapLogger.txt ;

- Methods
    - public static [log](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/log.md)() : void
    - public static [logg](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/logg.md)(...$args) : void
    - private static [getLogMessage](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/getLogMessage.md)($thing) : string

}




Properties
=============

- <span id="property-path"><b>path</b></span>

    This property holds the path for this instance.
    
    



Methods
==============

- [CheapLogger::log](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/log.md) &ndash; Logs the given argument(s) to the log file.
- [CheapLogger::logg](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/logg.md) &ndash; Deletes the log file, then recreate it and logs the given argument(s) in it.
- [CheapLogger::getLogMessage](https://github.com/lingtalfi/CheapLogger/blob/master/doc/api/Ling/CheapLogger/CheapLogger/getLogMessage.md) &ndash; Converts the given thing into a log string, and returns it.





Location
=============
Ling\CheapLogger\CheapLogger<br>
See the source code of [Ling\CheapLogger\CheapLogger](https://github.com/lingtalfi/CheapLogger/blob/master/CheapLogger.php)



