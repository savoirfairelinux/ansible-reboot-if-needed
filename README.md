# reboot-if-needed

Reboots hosts if needed. After having rebooted, we wait for the hosts to be up before continuing
the play.

Because rebooting can happen at a bad time, we pause before each reboot to give the opportunity
to cancel the play. It is thus recommended to tag your invocation of this role so that you can
exclude it if needed, or if you run your play in an unattended environment.
