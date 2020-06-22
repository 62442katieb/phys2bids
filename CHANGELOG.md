# v2.0.0 (Mon Jun 15 2020)

:tada: This release contains work from a new contributor! :tada:

Thank you, Molly Bright ([@BrightMG](https://github.com/BrightMG)), for all your work!

#### 💥 Breaking Change

- Make heuristics a simple set of "if .. elif .. else" statements and use a dictionary instead of variables. [#209](https://github.com/physiopy/phys2bids/pull/209) ([@smoia](https://github.com/smoia))

#### 🚀 Enhancement

- Add BIDS-compatible automatic reformatting of units of measure [#222](https://github.com/physiopy/phys2bids/pull/222) ([@vinferrer](https://github.com/vinferrer) [@smoia](https://github.com/smoia) [@eurunuela](https://github.com/eurunuela))
- Add `getitem` and `eq` methods to BlueprintInput for easier slicing and comparing [#213](https://github.com/physiopy/phys2bids/pull/213) ([@smoia](https://github.com/smoia))
- Improve code compliance to BIDS in BlueprintOputput [#189](https://github.com/physiopy/phys2bids/pull/189) ([@smoia](https://github.com/smoia))

#### 🐛 Bug Fix

- Auto [#236](https://github.com/physiopy/phys2bids/pull/236) ([@smoia](https://github.com/smoia))
- Check branch in travisCI [#235](https://github.com/physiopy/phys2bids/pull/235) ([@smoia](https://github.com/smoia))
- Print float to max 4 decimal places [#212](https://github.com/physiopy/phys2bids/pull/212) ([@RayStick](https://github.com/RayStick))
- Enh/bids units [#224](https://github.com/physiopy/phys2bids/pull/224) ([@smoia](https://github.com/smoia))
- Add issue templates [#220](https://github.com/physiopy/phys2bids/pull/220) ([@smoia](https://github.com/smoia))

#### ⚠️ Pushed to `master`

- Update ISSUE_TEMPLATE_MEETING.md ([@smoia](https://github.com/smoia))
- Update badges ([@smoia](https://github.com/smoia))
- Invert Cesar & Vicente, reorganise badges ([@smoia](https://github.com/smoia))
- Update heuristic.rst ([@smoia](https://github.com/smoia))
- Add heuristic link ([@smoia](https://github.com/smoia))
- Update card link ([@smoia](https://github.com/smoia))
- Add card and mattermost channel for BrainWeb ([@smoia](https://github.com/smoia))
- Add card for BrainWeb ([@smoia](https://github.com/smoia))
- Updates for the BrainWeb ([@smoia](https://github.com/smoia))
- Triggger Travis CI ([@smoia](https://github.com/smoia))

#### 📝 Documentation

- Add guidelines for PR reviews. [#197](https://github.com/physiopy/phys2bids/pull/197) ([@smoia](https://github.com/smoia) [@RayStick](https://github.com/RayStick))
- Update reference API [#231](https://github.com/physiopy/phys2bids/pull/231) ([@rmarkello](https://github.com/rmarkello))
- Add "Why BIDS?" page to the documentation [#229](https://github.com/physiopy/phys2bids/pull/229) ([@rmarkello](https://github.com/rmarkello))
- Create LICENSE [#3](https://github.com/physiopy/phys2bids/pull/3) ([@smoia](https://github.com/smoia))
- Fix typos on "Best Practices for Phys Data Collection" [#200](https://github.com/physiopy/phys2bids/pull/200) ([@kristinazvolanek](https://github.com/kristinazvolanek))
- Fix formatting on "Best Practices for Phys Data Collection" [#198](https://github.com/physiopy/phys2bids/pull/198) ([@kristinazvolanek](https://github.com/kristinazvolanek))
- Update trigger detection tutorial [#191](https://github.com/physiopy/phys2bids/pull/191) ([@vinferrer](https://github.com/vinferrer) [@RayStick](https://github.com/RayStick) [@smoia](https://github.com/smoia))
- Add section on "Best Practices for Phys Data Collection" [#177](https://github.com/physiopy/phys2bids/pull/177) ([@AyyagariA](https://github.com/AyyagariA) [@BrightMG](https://github.com/BrightMG))
- Update viz.py docstrings and Inputs [#193](https://github.com/physiopy/phys2bids/pull/193) ([@vinferrer](https://github.com/vinferrer))
- Create README.md [#4](https://github.com/physiopy/phys2bids/pull/4) ([@smoia](https://github.com/smoia))

#### ⚠️ Tests

- Fix azure pipelines non-failure bug [#223](https://github.com/physiopy/phys2bids/pull/223) ([@rmarkello](https://github.com/rmarkello))
- Add Azure Pipelines for Windows CI testing [#208](https://github.com/physiopy/phys2bids/pull/208) ([@rmarkello](https://github.com/rmarkello))

#### 🏠 Internal

- Add required token for Travis to run auto [#240](https://github.com/physiopy/phys2bids/pull/240) ([@smoia](https://github.com/smoia))
- Fix Travis CI environment for auto [#238](https://github.com/physiopy/phys2bids/pull/238) ([@smoia](https://github.com/smoia))
- Fix TravisCI configuration for auto [#237](https://github.com/physiopy/phys2bids/pull/237) ([@smoia](https://github.com/smoia))
- Implement automatic release [#181](https://github.com/physiopy/phys2bids/pull/181) ([@smoia](https://github.com/smoia))
- Move bids-related functions to dedicated file [#234](https://github.com/physiopy/phys2bids/pull/234) ([@smoia](https://github.com/smoia))
- Remove bioread form required dependencies, ease extra modules installation [#214](https://github.com/physiopy/phys2bids/pull/214) ([@smoia](https://github.com/smoia) [@RayStick](https://github.com/RayStick))
- Reordering of import statements in the entire phys2bids project [#195](https://github.com/physiopy/phys2bids/pull/195) ([@eurunuela](https://github.com/eurunuela))

#### Authors: 8

- Apoorva Ayyagari ([@AyyagariA](https://github.com/AyyagariA))
- Eneko Uruñuela ([@eurunuela](https://github.com/eurunuela))
- Kristina Zvolanek ([@kristinazvolanek](https://github.com/kristinazvolanek))
- Molly Bright ([@BrightMG](https://github.com/BrightMG))
- Rachael Stickland ([@RayStick](https://github.com/RayStick))
- Ross Markello ([@rmarkello](https://github.com/rmarkello))
- Stefano Moia ([@smoia](https://github.com/smoia))
- Vicente Ferrer ([@vinferrer](https://github.com/vinferrer))
