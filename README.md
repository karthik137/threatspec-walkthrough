# threatspec-walkthrough
Threatspec-walkthrough


#### Prerequisites

1) graphviz
2) threatspec


##### Install prerequisites

> Install graphviz

```
sudo apt-get install graphviz
```

> Install threatspec

```
pip3 install threatspec
```


##### Clone sample threat spec project

```
$ git clone https://github.com/threatspec/threatspec_example_report.git
```

```
$ cd threatspec_example_report
```

##### Initialize threatspec

```
$ threatspec init
```

##### Run threatspec

```

$ threatspec run
Running threatspec...

Threatspec has been run against the source files. The following threat mode file
has been created and contains the mitigations, acceptances, connections etc. for
the project:

    threatmodel/threatmodel.json

The following library files have also been created:

    threatmodel/threats.json threatmodel/controls.json threatmodel/components.json

```

##### Generate threatspec report


```
$ threatspec report
```



