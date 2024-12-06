# HyperFlow
HyperFlow is my solo project to create an imperative language that was originally designed to manage files and directories, but has now evolved to manage processes. It is a shell-based imperative language, which I call 'Prompt Language.

# The HyperFlow structure is designed to be both easy to read and simple to write.
It operates as follows:

# <action-call> <function> <parameters>;

Where the action-call serves as a library to invoke the associated functions, and the parameters define the specific details for those functions.

mng: Action-call for management operations.
cxt: Action-call for context-related operations.
sis: Action-call for system processes.

Functions are invoked via the . (dot) operator.

Example:
mng .cr folder: "c:\workspace", nm: "NEW FOLDER", upper: first;
EXIT: "New Folder"
