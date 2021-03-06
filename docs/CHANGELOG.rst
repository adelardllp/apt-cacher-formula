
Changelog
=========

`0.7.2 <https://github.com/saltstack-formulas/apt-cacher-formula/compare/v0.7.1...v0.7.2>`_ (2019-10-12)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** add fixes using ``rubocop --safe-auto-correct`` (\ ` <https://github.com/saltstack-formulas/apt-cacher-formula/commit/e8c455f>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/apt-cacher-formula/commit/d44e3c6>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ ` <https://github.com/saltstack-formulas/apt-cacher-formula/commit/22a91f7>`_\ )

`0.7.1 <https://github.com/saltstack-formulas/apt-cacher-formula/compare/v0.7.0...v0.7.1>`_ (2019-10-10)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **map.jinja:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/apt-cacher-formula/commit/abba9c1>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/apt-cacher-formula/commit/8913f37>`_\ )

`0.7.0 <https://github.com/saltstack-formulas/apt-cacher-formula/compare/v0.6.0...v0.7.0>`_ (2019-10-07)
------------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **states:** fix template lookup in apt-cacher/ng/client/config (\ `1b288c2 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/1b288c2>`_\ )
* **states:** rename states in a more consistent way (\ `d1b56c2 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/d1b56c2>`_\ )
* **tofs:** rename default config files (\ `a20a724 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/a20a724>`_\ )

Code Refactoring
^^^^^^^^^^^^^^^^


* **states:** split client.sls and server.sls in sub-states (\ `566e38d <https://github.com/saltstack-formulas/apt-cacher-formula/commit/566e38d>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `ca98247 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/ca98247>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `b4d6d97 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/b4d6d97>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `652706f <https://github.com/saltstack-formulas/apt-cacher-formula/commit/652706f>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `cdf6b50 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/cdf6b50>`_\ )

Documentation
^^^^^^^^^^^^^


* **pillar:** add pillar example for TOFS pattern (\ `d08ed97 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/d08ed97>`_\ )

Features
^^^^^^^^


* **map:** sync map.jinja with template-formula (\ `2b4c4d5 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/2b4c4d5>`_\ )
* **tofs:** add tofs pattern (\ `1a7dd94 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/1a7dd94>`_\ )

Tests
^^^^^


* **inpsec:** test apt-cacher client config (\ `81bb9db <https://github.com/saltstack-formulas/apt-cacher-formula/commit/81bb9db>`_\ )
* **inspec:** check that apt-cacher-ng port is opened (\ `19acc34 <https://github.com/saltstack-formulas/apt-cacher-formula/commit/19acc34>`_\ )

`0.6.0 <https://github.com/saltstack-formulas/apt-cacher-formula/compare/v0.5.0...v0.6.0>`_ (2019-09-20)
------------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** add Kitchen tests (\ `265aa5a <https://github.com/saltstack-formulas/apt-cacher-formula/commit/265aa5a>`_\ )

Features
^^^^^^^^


* **semantic-release:** add semantic-release (\ `03bf55c <https://github.com/saltstack-formulas/apt-cacher-formula/commit/03bf55c>`_\ )
