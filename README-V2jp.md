# Enhanced photo blog publisher

## Project Title.
�Ȉ�Easy Photo Blog ���e�c�[��������

## Elevator Pitch.
�gEnhanced photo blog publisher�h �̓N���E�h�Ή��A�ȒP�Ɏʐ^�t�����e���邽�߂̃A�v��, ���e�r���[�A�A�J�X�^���F�؁Abase64 encode �����ȂǁA�������ꂽ�o�[�W�����ł���B

## Description.
�Ȉ�Easy Photo Blog ���e�c�[���̓X�}�[�g�t�H���̃A�v���A�ȒP�Ɏ�����WordPress�T�C�g�ɁA�ʐ^�t�����e���邽�߂̂��́B���L�̋@�\�������ꂽ:
1.	���e�r���[�A�ōŋ߂̓��e�������B
2.	�J�X�^���F�؉�ʂŁA������WordPress REST API�̃T�[�r�X���܂߂郊�X�g���Ǘ��\.

���̃A�v���ɂ����炷�Љ�I���v�́A�ʐ^�t�����e���v���A�ȒP�ɂł��邽�߁A���Ƃł�����茩�����ł���̂�, �l�X�ɂ������񓊍e���郂�`�x�[�V������^���邱��. ����� [WordPress REST API](http://wp-api.org/)�@�g�����߂̂�������ɂȂ�.

![](./PhotoBlog2app.png)

WordPress REST API�Ή�WordPress�T�C�g�ɓ��e�������e�̉�ʃR�s�[

![](./PhotoBlog2web.png)

## Download and Test.
���̃A�v���� WordPress REST API�g������, �S�Ă̋@�\���e�X�g����ɂ́AWordPress��REST API������K�v. �������[�e�X�g�T�C�g](http://wp-api.pw/)�����R�ɗ��p���Ă��\��Ȃ�. �A�v�����_�E�����[�h����ɂ́AMIT AI2 Companion�A�v���܂��̓X�L���i�[�A�v�����g����QR�R�[�h���X�L�������āA �܂��� [���̃_�E�����[�h�����N���N���b�N����](https://sites.google.com/site/chen420/my-apk/PhotoBlog%20%281%29.apk?attredirects=0&d=1).

![](./PhotoBlog2download.png)

## Technical Description.
���L�̉�ʃR�s�[�ɂ���悤�ɁA���̃A�v���̓v���W�F�N�g�̍Œ���d�l�𖞂������B���� 2 �O���[�o���ϐ��iglobal variables�j, 4 ���X�g�f�[�^�ilist data�j, 2�֐��iprocedures or functions�j, ������ 2 ��if/else �\���istructure�j���܂܂ꂽ�B

![](./PhotoBlog2blocks.png)

##   Appendix.

### WP REST API web service
WP REST API��WordPress�̃v���O�C���A ������ WordPress�R�A�ɑg�ݓ���AWordPress�� �u���O�v���b�g�t�H�[��/CMS ����A�{�i�I�ȃA�v���P�[�V�����E�t���[�����[�N�֕ϐg���邽�߂Ɉ���ł���B
To start a service, you have own a own WordPress site, and use 2 plugins:
1.	WP REST API plugin, install and active (schedule uptake to core WP 4.4 and WP 4.5)
2.	BASIC Auth plugin, git clone https://github.com/WP-API/Basic-Auth basicAuth, and active.

### tinywebdb-base64 web service
WP REST API �� OAuth 1.0a ��Basic Auth �F�ؕ��@�T�|�[�g����B ������App Inventor��OAuth 1.0a�Ή��ł��Ȃ�����, Basic Auth�𗘗p�����BBasic Auth ��base64 encode�𗘗p����. ������App Inventor�͂��̋@�\���Ȃ����߁A [tinywebdb-base64](https://edu2web.github.io/tinywebdb-base64/) �v���O�����������, ���̃v���O������ App Inventor ��Tinywebdb �@�\�𗘗p���āA value = base64_encode (tag)��base64 encode�����l�𗘗p����B tinywebdb-base64 �v���O�������T�[�o�ɃC���X�g�[�����A ���̃T�[�o�� URL ���v���O�����ɃZ�b�g����K�v������B����tinywebdb-base64 web service�����R�Ɏg���Ă�����.
