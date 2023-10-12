###########################
sphinx やってみた2
###########################

| 違いを
| 作ってみる！

====== ================
ID      Value
====== ================
3      ほうきぼし
4      夏海
====== ================

.. seqdiag::
   :desctable:

   seqdiag {
      A -> B[label = "test"];
      B -> C[label = "test"];
      A [description = "browsers in each client"];
      B [description = "web server"];
      C [description = "database server"];
   }
