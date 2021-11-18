# Porter Test Me

Simple bundle with behaviors for testing workflows

## Usage

Run porter explain for details
```
porter explain --reference ghcr.io/bdegeeter/porter-test-me-installer:v0.1.0
```

```
Name: porter-test-me
Description: Porter bundle with test behaviors
Version: 0.1.0
Porter Version: v0.38.7

Credentials:
Name            Description                Required   Applies To
insecureValue   insecure test credential   false      All Actions

Parameters:
Name         Description                         Type      Default   Required   Applies To
delay        sleep (in seconds) before exiting   integer   0         false      All Actions
exitStatus   control exit status code            integer   0         false      All Actions

Outputs:
Name            Description                  Type      Applies To
outAction       bundle action                string    All Actions
outDelay        delay parameter value        integer   All Actions
outExitStatus   exitStatus parameter value   integer   All Actions

No custom actions defined

No dependencies defined

```
