# avro_reader_writer
Read and write avro files with groovy and NiFi

Avro is a very compact file format compared to CSV wich makes it good from an execution point to use when doing 
multiple processeing of a file

Avro is also the standarf format that you get from DB integrations, so its good to keep the original format 
instead of converting it to a CSV file especialy if the data contains binary information

This small groocy script is just showing how to use avro with groovy
It takes an avro stream as an input add one new record and send the data out again

