# Photoblog

## Project Title.
�Ȉ�Easy Photo Blog ���e�c�[��

## Elevator Pitch.
���̃N���E�h�Ή��A�v���́A�X�}�[�g�t�H���̎ʐ^�M�������[����ʐ^��I�сA������WordPress�T�C�g�̃��f�C�A�t�@�C���ɕۑ����C���̎ʐ^���܂߂铊�e���쐬����.

## Description.
�Ȉ�Easy Photo Blog ���e�c�[���̓X�}�[�g�t�H���̃A�v���A�ȒP�Ɏ�����WordPress�T�C�g�ɁA�ʐ^�t�����e���邽�߂̂��́B���̃X�e�b�v�œ��e����:

1. �^�C�g������
1. �ʐ^�M�������[����ʐ^��I��
1. �gPost to media�h�{�^���������AWordPress�T�C�g�̃��f�C�A�t�@�C���ɕۑ�����
1. ���e������e����͂���
1. �gPost Blog�h�{�^���������A�ʐ^�t�����e���������� .

���̃A�v���́A������WordPress�T�C�g�Ɏʐ^�t�����e���y�ɂ�����̂ł���.

���̃A�v���ɂ����炷�Љ�I���v�́A�ʐ^�t�����e���v���A�ȒP�ɂł��邽�߁A���Ƃł�����茩�����ł���̂�, �l�X�ɂ������񓊍e���郂�`�x�[�V������^���邱��. ����� [WordPress REST API](http://wp-api.org/)�@�g�����߂̂�������ɂȂ�.

![](./appview.png)

## Download and Test.
���̃A�v���� WordPress REST API�g������, �S�Ă̋@�\���e�X�g����ɂ́AWordPress��REST API������K�v. �������[�e�X�g�T�C�g](http://wp-api.pw/)�����R�ɗ��p���Ă��\��Ȃ�. �A�v�����_�E�����[�h����ɂ́AMIT AI2 Companion�A�v���܂��̓X�L���i�[�A�v�����g����QR�R�[�h���X�L�������āA �܂��� [���̃_�E�����[�h�����N���N���b�N����](https://sites.google.com/site/chen420/my-apk/PhotoBlog%20%281%29.apk?attredirects=0&d=1).

![](./apkdownload-1.png)

WordPress REST API�Ή�WordPress�T�C�g�ɓ��e�������e�̉�ʃR�s�[

![](./appwebview.png)

## Technical Description.
���L�̉�ʃR�s�[�ɂ���悤�ɁA���̃A�v���̓v���W�F�N�g�̍Œ���d�l�𖞂������B���� 2 �O���[�o���ϐ��iglobal variables�j, 4 ���X�g�f�[�^�ilist data�j, 2�֐��iprocedures or functions�j, ������ 2 ��if/else �\���istructure�j���܂܂ꂽ�B

![](./blocksview.png)

## Appendix.

WP REST API��WordPress�̃v���O�C���A ������ WordPress�R�A�ɑg�ݓ���AWordPress�� �u���O�v���b�g�t�H�[��/CMS ����A�{�i�I�ȃA�v���P�[�V�����E�t���[�����[�N�֕ϐg���邽�߂Ɉ���ł���B

WP REST API �� OAuth 1.0a ��Basic Auth �F�ؕ��@�T�|�[�g����B ������App Inventor��OAuth 1.0a�Ή��ł��Ȃ�����, Basic Auth�𗘗p�����BBasic Auth ��base64 encode�𗘗p���邪�A�����App Inventor�����ł͌v�Z�ł��Ȃ�, �����炱�̃A�v���́A�O���[�o���ϐ��iglobal variable�j�� �\��base64 encode�v�Z�����l������B
