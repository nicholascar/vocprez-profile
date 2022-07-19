# VocPrez Profile
This is a *profile* of another profile, the [VocPub Profile](https://w3id.org/profile/vocpub), which profiles the [Simple Knowledge Organization System (SKOS)](https://www.w3.org/TR/skos-reference/). It is implemented to allow for the validation of vocabularies according to the needs of the [VocPrez](https://github.com/surroundaustralia/Prez/) tool.

By *profile*, what is meant here is "A specification that constrains, extends, combines, or provides guidance or explanation about the usage of other specifications." (from [PROF](https://www.w3.org/TR/dx-prof/#definitions)) and, here the *other specifications* are VocPub & SKOS.

So this profile inherits all the requirements of SKOS and VocPub and adds a few of its own. Data conforming to this profile must therefore conform to VocPub and SKOS too.

This profile is formulated according to the [Profiles Vocabulary](https://www.w3.org/TR/dx-prof/) and provides [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/) validator files that can be used to determine whether vocabularies conform to this profile.

This profile is hosted online in [Linked Data](https://www.w3.org/standards/semanticweb/data) form using a persistent web address:

* <https://w3id.org/profile/vocprez>


## Profile Resources

### Specification
This profile's _specification_ - the resource that contains the normative rules - is within the file [specification.html](specification.html) and it is able to be viewed online at:

* <https://nicholascar.com/vocprez-profile/specification.html>

### Validator
This profile's rules, as defined in the _specification_ are presented for machine validation of RDF vocabularies in the shape file [validator.shacl.ttl](validator.shacl.ttl) which conforms to the [SHACL](https://www.w3.org/TR/shacl/) standard.

Tools such as [pySHACL](https://github.com/RDFLib/pySHACL) and the online [SHACL Playground](https://shacl.org/playground/) or [SHACL Play!](https://shacl-play.sparna.fr/play/) can be used with this shape file to validate vocabulary files.

## License  
This code is licensed using the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence. See the [LICENSE file](LICENSE) for the deed. 

Note [Citation](#citation) below for attribution.


## Citation
To cite this profile, please use the following (formulated in [BibTex](http://www.bibtex.org/)):

```
@software{vocpub-profile,
  author = {{Nicholas J. Car}},
  title = {{VocPrez Profile}},
  version = {1.1},
  date = {2022},
  url = {https://w3id.org/profile/vocprez}
}
``` 


## Contact

*creator:*  
**Dr Nicholas J. Car**  
*Data Architect*  
Kurrawong AI  
<nick@kurrawong.net>  
<https://orcid.org/0000-0002-8742-7730>
