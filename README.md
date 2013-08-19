Joda-Time-I18N
--------------

[Joda-Time](http://www.joda.org/joda-time/) provides a complete quality alternative to the JDK date and time classes.
Many aspects of date and time require internationalized data.
This project provides access to additional I18N data not supplied as part of the standard Joda-Time release. 

- Time zones by territory
- First day of week by territory
- Business week by territory
- Weekend by territory

As a flavour of the functionality, here's how to find out what days are the weekend in Egypt:

    Territory t = Territory.forID("EG");
    int weekendStartDay = t.getWeekendStart();
    int weekendEndDay = t.getWeekendEnd();

Joda-Time-I18N is licensed under the business-friendly [Apache 2.0 licence](http://www.joda.org/joda-time-18n/license.html).


### Documentation
Various documentation is available:

* The [home page](http://www.joda.org/joda-time-i18n/)
* The [Javadoc](http://www.joda.org/joda-time-i18n/apidocs/index.html)
* The change notes for the [releases](http://www.joda.org/joda-time-i18n/changes-report.html)


### Support
Please use GitHub issues and Pull Requests for support.
