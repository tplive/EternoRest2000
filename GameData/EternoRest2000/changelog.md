# Changelog  
  
| modName    | Eterno-Rest 2000 (REST)                                           |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | Aphotonites, Acea_ and zer0Kerbal                                 |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209894-*/) |
| github     | (https://github.com/zer0Kerbal/EternoRest2000)                    |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/EternoRest2000)       |
| spacedock  | (https://spacedock.info/mod/3126)                                 |
| ckan       | EternoRest2000                                                    |

## Version 1.2.99.0-release `<Thank you Aphtonites and Acea_>`

* 25 Sep 2022
* Released for Kerbal Space Program 1.12.3

### Adoption by zer0Kerbal

### Documentation 1.2.99.0

* Create
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [Disclaimer.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #6 - Create GitHub Pages
* Update
  * <EternoRest2000.version>
  * Remove [KSP_VERSION_MAX]

### Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
    * model.mu --> spacecoffin.mu
  * textures to unique names
    * model000.dds --> coffin00.dds
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* closes #10 - Part Asset Updates

### ImgBot

| File                        | Before         | After          | Percent reduction |
| :-------------------------- | :------------- | :------------- | :---------------- |
| /img/hero-01.png            | 1,232.77kb     | 1,034.80kb     | 16.06%            |
| /img/hero-02.png            | 1,182.42kb     | 1,022.17kb     | 13.55%            |
| /img/HeroLogo_1920x1920.png | 2,686.38kb     | 2,416.66kb     | 10.04%            |
| /img/HeroLogo_1920x1920.jpg | 366.06kb       | 345.97kb       | 5.49%             |
|                             |                |                |                   |
| **Total :**                 | **5,467.63kb** | **4,819.59kb** | **11.85%**        |
</details>
* closes #37 - [ImgBot] Optimize images

### Localization

* Localize parts
* Create Localization/
  * <en-us.cfg>
  * [readme.md] v2.1.2.0
  * [quickstart.md] v1.0.1.1
* Hero.png
* Thumbnails
  * @thumbs/
  * add thumbnails
* closes #43 - Create Thumbs
* closes #14 - English <us-en.cfg>
* closes #13 - Localization - Master
* closes #11 - Create <EternoRest2000>.cfg
* closes #9 - Create Localization directory and contents
* closes #7 - Create HeroLogo.png
* closes #31 - Part Localization

### Parts 1.2.99.0

* Update pass
* header
* update
  * file name from <part.cfg> --> <spacecoffin.cfg>
  * part name from SpaceVoffin --> rest-spacecoffin
  * [category] to Utility from Science
  * [entryCost] from 0 to 1000

### Compatibility 1.2.99.0

* Add [KerbalAttachmentSystem.cfg] v1.0.0.0

### Update License

* Updated License: GPL-2.0
  * was: The Unilicense
* closes #12 - Update License

### Status 1.2.99.0

* Issues
  * closes #2 - Eterno-Rest 2000 (REST) 1.2.99.0-adoption `<Thank you Aphtonites and Acea_>` edition
  * closes #3 - 1.2.99.0 Create Legal Mumbo Jumbo
  * closes #4 - 1.2.99.0 Create Documentation
  * closes #5 - 1.2.99.0 Create Social Media Presence

---

## Version 1.2.0.0-release `<Archival>`

* 21 Jan 2016
* Released for Kerbal Space Program 1.0.5 (1.0.0)

* Multiple updates to get it compatible with 1.0+.

### Status 1.2.0.0

* Issues
  * closes #8 - Archival Releases
  * closes #34 - 1.2.0.0-release

---

## Version 1.1.0.0-release `<Archival>`

* 27 Jun 2014
* Released for Kerbal Space Program 0.24.2 (0.22)

* adoption by Acea_
* Added tech tree support to the old 0.18 CFG(which has been nearly rewritten).
* Added KAS support.
* Now a coffin can be attached to another part or the ground.

### Status 1.1.0.0

* Issues
  * closes #33 - 1.1.0.0-release
  * updates #8 - Archival Releases

---

## Version 1.0.0.0-release `<Archival>`

* originally by Aphotonites

### Status 1.0.0.0

* Issues
  * closes #32 - 1.0.0.0-release
  * updates #8 - Archival Releases

---