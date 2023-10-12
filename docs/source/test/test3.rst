###########################
sphinx やってみた3
###########################

| 試しに、こんな感じのページを
| 作ってみる！

====== ================
ID      Value
====== ================
3      とりあえず
4      アミーゴ
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
