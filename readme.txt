��ģ�����ctex��aloft��CASthesis�����˼��޸ģ��ڴ˸�лԭ���ߡ�

��������������������������������������������������������������������������������������������������������������������

�ṩ��dvips��dvipdfm��pdftex�ı���ѡ��

�ṩ��oneside��twoside�ĵ�˫��ѡ��

��������������������������������������������������������������������������������������������������������������������

�ṩ��ʹ��MathTimePro�����ѡ����������ҵ���壬ȱʡ��ʹ�á���ϣ��ʹ�ã���ȥ��USTCthesis.cls�����²��ֵ�ע�͡�
%% using the MathTimeProfessional Font Supplement A
\let\Bbbk\relax
\let\heavymath\relax
\RequirePackage{mtpro,mtpams}

�ṩ��Ŀ¼�а���Ӣ�ĵ��±��������л�ѡ��ȱʡΪhelvetica����ϣ��ʹ����ͨtimes���壬��ע�͵�USTCthesis.cls�����²��֣�
%% chang chapter font in content 
\renewcommand*\l@chapter[2]{%
  \ifnum \c@tocdepth >\m@ne
    \addpenalty{-\@highpenalty}%
    \vskip 1.0em \@plus\p@
    \setlength\@tempdima{1.5em}%
    \begingroup
      \parindent \z@ \rightskip \@pnumwidth
      \parfillskip -\@pnumwidth
      \leavevmode \usefont{T1}{phv}{m}{n} \hei \zihao{-4}
      \advance\leftskip\@tempdima
      \hskip -\leftskip
      #1\nobreak\hfil \nobreak\hb@xt@\@pnumwidth{\hss #2}\par
      \penalty\@highpenalty
    \endgroup
  \fi}

�������Ӧʹ���п��壬���󲿷�TeXϵͳû�а�װ����ȱʡʹ�ú��塣����ͨ��USTCthesis.cfg�е�xk���嶨���޸ġ�

��������ѡ��������ļ���ע������ѡ��

��������������������������������������������������������������������������������������������������������������������

ģ��ʹ����ctex������������������°汾��
http://wikka.ctex.org/PackageCTeX

CJKpunct��������ڽ�����ı��ѹ�����Ѿ��������°�ctex����ڣ�������������
http://lsec.cc.ac.cn/cgi-bin/viewcvs.cgi/cct/CJKpunct/

cjk���µ���4.6����4.5�кܴ�Ľ�����Ȼ�°治�Ǳ��룬��������Ҳû������
http://cjk.ffii.org/cjk-current.tar.gz

���⻹���˺ܶ�����ams�ĺ�������ϣ��ʹ����TeXϵͳ�Ƚ�������

��������������������������������������������������������������������������������������������������������������������

��֪bug

1.�½ڱ������ʱ��ҳü�������ֿ��ܳ����ص�
  so��ȡ�̵�ı����

2.

���������������������������������������������������һ���ָ����ˣ���������������������������������������������������

�ҵ���ϵ��ʽ maya@嫺�����
