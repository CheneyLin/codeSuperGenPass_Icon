# codeSuperGenPass_Icon

#### 项目介绍
IconFont

#### 项目地址

http://iconfont.cn/manage/index?manage_type=myprojects&projectId=862721&keyword=

#### 测试

http://www.70apps.com/app/com.gpwzw.SuperGenPass/logo/?domain=reddit.com&theme=

#### TODO
insert into tblAPPSGPDomainIcon (domain) values ('mgtv.com')
insert into tblAPPSGPDomainIcon (domain) values ('weixin.com')
insert into tblAPPSGPDomainIcon (domain) values ('taobao.com')
insert into tblAPPSGPDomainIcon (domain) values ('youku.com')
insert into tblAPPSGPDomainIcon (domain) values ('facebook.com')
insert into tblAPPSGPDomainIcon (domain) values ('google.com')
insert into tblAPPSGPDomainIcon (domain) values ('qq.com')
insert into tblAPPSGPDomainIcon (domain) values ('twitter.com')
insert into tblAPPSGPDomainIcon (domain) values ('alipay.com')
insert into tblAPPSGPDomainIcon (domain) values ('line.com')
insert into tblAPPSGPDomainIcon (domain) values ('instagram.com')
insert into tblAPPSGPDomainIcon (domain) values ('apple.com')
insert into tblAPPSGPDomainIcon (domain) values ('slack.com')
insert into tblAPPSGPDomainIcon (domain) values ('teamviewer.com')
insert into tblAPPSGPDomainIcon (domain) values ('github.com')
insert into tblAPPSGPDomainIcon (domain) values ('paypal.com')
insert into tblAPPSGPDomainIcon (domain) values ('amazon.com')
insert into tblAPPSGPDomainIcon (domain) values ('trello.com')
insert into tblAPPSGPDomainIcon (domain) values ('getpocket.com')
insert into tblAPPSGPDomainIcon (domain) values ('51job.com')
insert into tblAPPSGPDomainIcon (domain) values ('reddit.com')
insert into tblAPPSGPDomainIcon (domain) values ('baidu.com')
insert into tblAPPSGPDomainIcon (domain) values ('163.com')
insert into tblAPPSGPDomainIcon (domain) values ('ctrip.com')
insert into tblAPPSGPDomainIcon (domain) values ('xing.com')


#### 数据

delete from tblAPPSGPDomainRequest where ip in (select ip from tblAPPSGPDomainRequest where domain='70apps.com')


/**********************************************************************
*****    类型:数据表
*****    名称:tblAPPSGPDomainIcon
*****    标题:已上线图标
*****    备注:-
*****    日期:2018/11/30 10:04:29
*****    版权:All4One 1.0.0
**********************************************************************/
--DROP TABLE tblAPPSGPDomainIcon
CREATE TABLE tblAPPSGPDomainIcon(
 [ID] [decimal](18, 0) IDENTITY(1,1) NOT NULL,
 [domain] [varchar](20) NOT NULL CONSTRAINT [DF_tblAPPSGPDomainIcon_domain]  DEFAULT ('-'),
	     CONSTRAINT [PK_tblAPPSGPDomainIcon] PRIMARY KEY CLUSTERED
(
	[ID] ASC
)
) ON [PRIMARY]
