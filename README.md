Toast's Aports
==============

A place for me (toast) to store my in-progress and personal aports.
You can consider anything you find here to be licensed under MIT if you so wish.
Alternatively, you can wait until (if ever) it's upstreamed into alpine, at which case it'll be available as per usual there.

A not-up-to-date repository (manually updated) with no stability guarantees should be available over at https://build.toastin.space
The key is available in its root: https://build.toastin.space/toast@toastin.space.rsa.pub

### FAQ

Q: How do I use this, despite all these terrible things you've said?

A:

```sh
wget https://build.toastin.space/toast@toastin.space.rsa.pub -P /etc/apk/keys/
echo "@toast https://build.toastin.space/toast" >> /etc/apk/repositories
```

Q: Can I have one without TLS (http://)?

A: No.
