# Changelog

This file was generated using [@jscutlery/semver](https://github.com/jscutlery/semver).

## [1.0.1](https://stash.ria.ee/scm/sun/veera-components/compare/styles-1.0.0...styles-1.0.1) (2022-09-27)


### Bug Fixes

* notification icon position and color (Pull request [#67](https://stash.ria.ee/scm/sun/veera-components/issues/67)) ([ab08190](https://stash.ria.ee/scm/sun/veera-components/commits/ab08190a02e233a999cc0edcb02f0e0aff92172b))



# [1.0.0](https://stash.ria.ee/scm/sun/veera-components/compare/styles-0.11.0...styles-1.0.0) (2022-09-27)


### Bug Fixes

* align icon and label to center ([4296fc0](https://stash.ria.ee/scm/sun/veera-components/commits/4296fc06d7ebbed8a2a458f4d106c2cc7c2a6eaa))


### Features

* notification changes (Pull request [#59](https://stash.ria.ee/scm/sun/veera-components/issues/59)) ([aba9f51](https://stash.ria.ee/scm/sun/veera-components/commits/aba9f5163d9e634b5bffdc73a808042955728946))


### BREAKING CHANGES

* type -> severity

Merge in SUN/veera-components from fix-compact-notification to master

Squashed commit of the following:

commit 6225e0a0f66f4981368cc1f3a614cbc29aede2e3
Merge: 16d0784 509cd81
Author: Sarah Marion Mikk <SarahMarion.Mikk@nortal.com>
Date:   Mon Sep 26 16:04:36 2022 +0300

    Merge branch 'master' into fix-compact-notification

    # Conflicts:
    #	libs/ui/src/lib/icons/labeled-icon/labeled-icon.component.html
    #	libs/ui/src/lib/notification/notification.html.stories.ts

commit 16d0784aed6dc4ee4729ec8fc903e67a07aa18ef
Author: Sarah Marion Mikk <SarahMarion.Mikk@nortal.com>
Date:   Mon Sep 26 16:00:33 2022 +0300

    refactor: lint

commit 64fe3a502bdb2a4493a6983d0b1826dec84ced37
Author: Sarah Marion Mikk <SarahMarion.Mikk@nortal.com>
Date:   Mon Sep 26 16:00:07 2022 +0300

    chore: icon for compact notification

commit a6991d4dbdcce665e4b0d3381a2775709e6ee9cb
Merge: 6d22672 0eba6f0
Author: Sarah Marion Mikk <SarahMarion.Mikk@nortal.com>
Date:   Mon Sep 26 14:37:07 2022 +0300

    Merge branch 'master' into fix-compact-notification

commit 6d22672618af3d8312aa713e177319f2b6fa69a1
Author: Aleksandr Beliaev <aleksandr.beliaev@nortal.com>
Date:   Fri Sep 23 20:46:53 2022 +0300

    refactor: Renamed type input of Notification component to severity and moved compact value to a separate input

commit 93bf9d3ea9bb4a92a5a0600785714021d86d346e
Author: Aleksandr Beliaev <aleksandr.beliaev@nortal.com>
Date:   Fri Sep 23 20:40:38 2022 +0300

    fix: replaced a font size in pixels in notification Sass component with a Veera variable

commit 4c97d7d3977b5e499b1560ee3fe1d5609de25e10
Author: Aleksandr Beliaev <aleksandr.beliaev@nortal.com>
Date:   Fri Sep 23 20:18:07 2022 +0300

    refactor: Renamed header input to title in Notification component to reflect better what it does

commit 18637fb54d46e01214ef1669b660d7f3d06f1ace
Author: Aleksandr Beliaev <aleksandr.beliaev@nortal.com>
Date:   Fri Sep 23 20:12:52 2022 +0300

    refactor: Refactored Notification component styles for better clarity and class consistency, simplified DOM structure, cleaned close, info and lightbulb SVG icons to allow for recoloring

commit 044b725afabc323444bef18c8ed55efa8bd84fca
Author: Aleksandr Beliaev <aleksandr.beliaev@nortal.com>
Date:   Fri Sep 23 19:58:22 2022 +0300

    fix: removed hardcoded size style from Icon Angular component

commit 39a29f2e5a987f9078527e0ee411c0453504422a
Author: Sarah Marion Mikk <SarahMarion.Mikk@nortal.com>
Date:   Fri Sep 23 13:42:23 2022 +0300

    fix: compact notifications with icon



# [0.11.0](https://stash.ria.ee/scm/sun/veera-components/compare/styles-0.10.1...styles-0.11.0) (2022-09-26)


### Features

* add an option to use an icon after the label ([61601eb](https://stash.ria.ee/scm/sun/veera-components/commits/61601ebc8a2bb210489ff557fe178f287ab3dd1a))



## [0.10.1](https://stash.ria.ee/scm/sun/veera-components/compare/styles-0.10.0...styles-0.10.1) (2022-09-26)


### Bug Fixes

* flip accordion icon when item active (Pull request [#60](https://stash.ria.ee/scm/sun/veera-components/issues/60)) ([0eba6f0](https://stash.ria.ee/scm/sun/veera-components/commits/0eba6f095be342e9ac31b7a4af24adb2918950d3))



# [0.10.0](https://stash.ria.ee/scm/sun/veera-components/compare/styles-0.9.0...styles-0.10.0) (2022-09-22)


### Features

* **styles:** remove unused import ([ca8bf32](https://stash.ria.ee/scm/sun/veera-components/commits/ca8bf32b556c7606d3c2665c4d6e4c248997a2bb))



# [0.9.0](https://stash.ria.ee/scm/sun/veera-components/compare/styles-0.8.4...styles-0.9.0) (2022-09-22)


### Bug Fixes

* stepper border color ([adeacef](https://stash.ria.ee/scm/sun/veera-components/commits/adeacefe144b0cc2cb6badbf0e324cfa5004cd25))
* stepper styles ([5f45c67](https://stash.ria.ee/scm/sun/veera-components/commits/5f45c67ad84ff4745610d0eb12c34f8b5e37e84b))
* steps visuals ([d1c6c1c](https://stash.ria.ee/scm/sun/veera-components/commits/d1c6c1cd1e126962d2e030b78713f032b4eb206c))
* tags ([20aa0cf](https://stash.ria.ee/scm/sun/veera-components/commits/20aa0cf459dbb5f5ca1ce92879830a014e60c9f9))


### Features

* icons library ([e5326f2](https://stash.ria.ee/scm/sun/veera-components/commits/e5326f2fe4d93e5b2b14cd9f53a61767f8398208))



## [0.8.5](https://bitbucket.ria.ee/scm/sun/veera-components/compare/styles-0.4.2...styles-0.8.5) (2022-09-21)



## [0.4.2](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.4.1...assets-0.4.2) (2022-09-21)


### Bug Fixes

* remove max width css property from notifications ([8382665](https://stash.ria.ee/scm/sun/veera-components/commits/8382665412d57c93cbd848d306301bb8aa957c94))



## [0.4.1](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.4.0...assets-0.4.1) (2022-09-20)


### Bug Fixes

* remove padding from html-section ([3d0700a](https://stash.ria.ee/scm/sun/veera-components/commits/3d0700a66d2f1d16d6dcc35bc14ea270aed99955))



# [0.4.0](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.3.0...assets-0.4.0) (2022-09-19)

### Features

- release versions ([ee70eb8](https://stash.ria.ee/scm/sun/veera-components/commits/ee70eb890914a3346bffd1461c71bd2cc01fbc7b))

# [0.3.0](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.2.0...assets-0.3.0) (2022-09-19)

### Features

- **angular:** notification component ([146ea73](https://stash.ria.ee/scm/sun/veera-components/commits/146ea7399f912ab1ad1b6cff9fa7c2e6e83d7968))

# [0.2.0](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.1.2...assets-0.2.0) (2022-09-17)

### Features

- step component mobile support & regular icons ([41f2e32](https://stash.ria.ee/scm/sun/veera-components/commits/41f2e320bd08d83933052b4e3555182e9e08a626))

## [0.1.2](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.1.1...assets-0.1.2) (2022-09-13)

### Bug Fixes

- change steps on click and change step content ([02e6d5b](https://stash.ria.ee/scm/sun/veera-components/commits/02e6d5b204fb8db3266e930e8101e9cfa1968651))

## [0.1.1](https://stash.ria.ee/scm/sun/veera-components/compare/assets-0.1.0...assets-0.1.1) (2022-09-08)

### Bug Fixes

- icon names ([7a318fc](https://stash.ria.ee/scm/sun/veera-components/commits/7a318fc9e2712c08a2996b6f0113cc4a9e46feeb))

# 0.1.0 (2022-09-08)

### Features

- add styles
- added form-item component
- added design tokens pages and intro to storybook
- added StepsComponent and StepComponent
- create labeled icon component
- accordion component
- feedback survey form
- add contacts block