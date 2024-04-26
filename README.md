# ICPE2024
Installing LTTng
Refrence: [https://lttng.org/docs/v2.13/#doc-ubuntu](https://lttng.org/docs/v2.13/#doc-ubuntu-ppa)

```
# apt-add-repository ppa:lttng/stable-2.13
# apt-get update
# apt-get install lttng-tools
# apt-get install lttng-modules-dkms
# apt-get install liblttng-ust-dev

```

LTTng commands
```
# systemctl status lttng-sessiond
# systemctl start lttng-sessiond
# lttng create
# lttng enable-event -k -a
# lttng start
# wget www.google.com
# lttng destroy

```

Installing TraceCompass
https://eclipse.dev/tracecompass/
