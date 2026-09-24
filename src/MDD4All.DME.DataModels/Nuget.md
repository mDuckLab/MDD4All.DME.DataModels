Sample data models for MDD4All.DME, an editor for object graphs.

Each folder is one small model, kept deliberately narrow so it shows a single thing:
objects inside objects, lists and arrays, a dictionary whose key is an object, read-only
properties, the data annotations the editor enforces, the DataType hints it turns into
different input controls, an enum.

The editor loads this assembly like any other data model - it is nothing the application
knows about beforehand, which is what makes it a useful thing to try it on.
