# PacketHacked

I managed to **decrypt, edit** and **repack** Cisco Packet Tracer file Format. So i publish all the **SOLVED EXERCISES** From CCNA v7.

## The Attack

Packet Tracer Exercises have a special **Admin Area**, Where we can view answers, and replace the exercise with an "already done" version by Cisco. This Area is protected by a Password. However packet tracer doesn't encrypt the content with that password, so by swapping the hash with an our hash, we can overwrite the file with the "solved version" and re-swap the hash with the original one, and we can solve the exercise without any effort.

### Warning

Before spreading this to every school in Italy. The files was crafted with our teacher password, You can use these files, but when other teachers try to log-in to admin area and get an error, they will eventually notice that something is wrong.
