# Patched version of jgrapht to make it compatible with GWT

## Changes

- Remove invocations of Object.clone()
- Remove references to CloneNotSupportedException
- Disable tests that did verify Graph.clone() behaviour on regular JVM's
- Replace Dequeue with Stack in StrongConnectivityInspector

For a full list of changes and further details please consult the commit log.