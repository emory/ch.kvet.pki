---
layout: page
title: Eyrie Certificates
---

Ahoy thar.

# Certificates generated by the Eyrie CA include:

## Certificate Authorities

* [Eyrie Root CA](eyrie_Root.crt) (PEM .crt)
* [Eyrie Intermediate CA](eyrie_Intermediate.crt) (PEM .crt)

### Or get both in one chained certificate:

* [Eyrie Authority Chain](eyrie_Chain.p7b) (.p7b)
	
## End-Entity (Users) 

* [Emory](eyrie_Emory.crt) (PEM .crt)
  * [Emory and Eyrie CA Authority Chain all-in-one](eyrie_Emory_chain.p7b) (.p7b) 

# CRL

Don't forget, you can get a probably-accurate-maybe-not-because-lazy [CRL](http://pki.kvet.ch/ca/crl/eyrie.crl) as well. The URI is included in all certificates, in case you forget.
