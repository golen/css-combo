# css-combo

## Introduction
combo css which import other css
����js��Ŀǰ�Ѿ��бȽϳ����ģ�黯����������seajs��kissy������css�����أ�һ����ͨ��less���б������ġ�less�ٷ�����less�ļ��е�@import "xxx.css"�ǲ����������ģ���Ҳ�ǿ��ǵ���������������Ҫ��������css���������@import "xxx.less"��less������߾ͻ������Щ�����ģ�飬���д����
css-combo���ǽ��������˼�룬ʵ����cssģ�黯����������ļ���@import����ģ�飬Ȼ�������ļ����д����ʱ�򣬸ù��߻����import���ļ�������Щ�ļ����������

## Usage

*API:*

    CssCombo.build(cfg);

* cfg:{Object} ����

    * target��{String} ����ļ�
    * inputEncoding��{String} �����ļ����룬��ѡ��Ĭ�ϼ������ļ��е�@charset���á��������ļ�û������@charset����ô������ñ�ѡ��
    * outputEncoding��{String} ����ļ����룬��ѡ��Ĭ��UTF-8�����ѡ����ѹ�������ᴦ����ascii
    * output��{String} ���Ŀ¼������ʹ�����·��
    * exclude��{Array} �������������飬��ѡ��Ĭ�ϲ�����[/.combine.css/, /-min.css/, /.combo.css/]
    * compress: {Boolean} �Ƿ�ѹ����Ĭ��Ϊtrue����������ͬYUICompressor
    * debug: {Boolean} �Ƿ��ӡ��־

## TODO

    * ����Ŀ¼�����ʽ
    * <del>���Ӷ�ģ��@charset�ļ��</del>
    * <del>����ת�������ѹ����ascii</del>

## License
css-combo ���� "MIT"��https://github.com/daxingplay/css-combo/blob/master/LICENSE.md Э��
