.. warning::
   
   In MongoDB 4.4 and later, if write operations use
   :writeconcern:`{ w: 1 } <\<number\>>` write concern, the rollback
   directory may exclude writes submitted after an :term:`oplog hole`
   if the primary restarts before the write operation completes.
