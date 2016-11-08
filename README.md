cltcl
=====
Embed Tcl/Tk scripts in Common Lisp

Forked version from lisper99/cltcl in order to get it into QuickLisp.

Documentation from  http://lisper99.github.io/cltcl/  added into folder
`doc`.

Example `package-viewer` slightly modified and added to folder `ex` such
that a quick test by `(load "package-viewer.lisp")` may be performed. You
probably have to adjust the following paths at the top of the file:

```lisp
;; Setup QuickLisp and load clTcl
(load "~/quicklisp/setup")
(ql:quickload :cltcl)

;; Define Tcl interpreter 
(defparameter *wish* "C:/Tcl/bin/wish86.exe")    ;; Windows
; (defparameter *wish* "/usr/bin/wish")          ;; Unix
```

See http://lisper99.github.io/cltcl/examples.html.

**Loadable from Quicklisp since 1-NOV-2016**

---



