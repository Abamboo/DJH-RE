#### NER with crf++
NER�����Ŀ���Ǵ��ı���ȡ���ض�����ʵ����ı�Ƭ�Σ����ڹ��򡢻���ģ�ͣ�
+ ����ģ�͵ķ�����
��ģ�͵ĽǶ�����������ʵ��ʶ������ʵ���������б�ע���⣬���������б�עģ�Ͱ���HMM��CRF��RNN��ģ��
+ CRF������
  1.��ȷ��ע����NER���Ը���ҵ�������ע���ֲ�ͬ���͵�ʵ�壬�������Ҫ��ȷ��Ҫ��ȡ��ʵ�����͡�һ��ͨ�ó����£����ȡ����ʱ�䡢����ص㼰��֯����������˱�������ȡTIME��PERSON��LOCATION��ORGANIZATION����ʵ�塣
  2.���ݼ�����׼������ȷ��������Ҫѵ�����ݺ�ģ�͹��ߣ�ѵ������ѡ�������ձ�1998���ı�ע���Ͽ⣻ģ�͹���ѡ��crf++
  3.����Ԥ������
    3.1���������ļ�����Ϊutf-8
    3.2�Ķ������Ͽ�Ĵ��Ա��˵��
    3.3���⻹��Ҫ�����Ͽ�Ĺ���ע�⣬����˵�����ձ����ϣ�ͨ���۲����Ͽ����ݣ���Ҫע���ĵ㣺1��1998���Ͽ��ע����ʱ�����պ����ֿ���ע�������Ҫ�ϲ�����;2���������������ļ����ʱ�ʾ�����ȷִʣ�����������ǿ����Ҫ�����������ݺϲ�;3��ʱ��ϲ������罫��1997��/t 3��/t�� �ϲ��ɡ�1997��3��/t��;4��ȫ���ַ�ͳһתΪ����ַ������������ֵı�ʾ
  4.ģ��ѵ�����������ǵ�NER��������CRF++��ѵ��Ҫ��ģ��ѵ����Ҫ4�����裺1��ȷ����ǩ��ϵ;2��ȷ������ģ���ļ�;3������ѵ�������ļ�;4��ģ��ѵ����
    4.1ȷ����ǩ��ϵ������NER���񣬳����ı�ǩ��ϵ����IO��BIO��BMEWO��BMEWO+
    4.2����ģ����ƣ�crf++������ģ��
    4.3ѵ���������ɣ��������ݸ�ʽҪ����ģ�͹���Ҫ��
    4.4ģ��ѵ������������...
  5.ģ�Ͳ��Լ�ʹ��
    5.1��ģ��Ԥ��ʱ��CRF++��Ҫʹ����ά�ر��㷨����nbest�������ģ��ѵ��ʱ������ָ��-t��������ı���ʽ��ģ�ͣ�����debug���д�Լ���ģ�ͼ��ؼ��������
    5.2����һ��������NER���̣����˵õ����б�ǩ�⣬��Ҫ�Ա�ǩ���н��н���õ����յĽ����CRF++ͬʱ�ṩ��python�ӿڣ����Է������python �����н���ģ�͵ĵ��õõ���ǩ���У�Ȼ��ͨ����ǩ����õ����յĽ��
  6.ģ���Ż�
    6.1���Ͽ�Ĺ�ģ����������ע
    6.2ģ������ѡ��
    6.3....
---
reference
[1](http://blog.csdn.net/weixin_36541072/article/details/53084409)
[2](http://zhuanlan.51cto.com/art/201705/540693.htm)