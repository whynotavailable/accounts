# Notes

For scheduling there are three types. Excepting Yearly they all have the format
of `<schedule type>:<comma seperated day numbers>:<periods to skip>`. Currently there are no plans to
have Yearly skips.

* Weekly
* Monthly
* Yearly

Weekly has 7 day numbers being the week days Sunday -> Saturday

Monthly has 31 day numbers being the day of month

Yearly has `<month>-<day>` combinations.

Since it's so paired down, I can fit it in a single string field and capture most scheduling situations.
