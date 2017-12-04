# Volley
Android Volley框架，基于谷歌最新的发布版本做了Android6.0的适配优化，没有增加其他功能。

SELECT tb_order.ordernum, tb_order.totalprice, tb_order.payprice, tb_order.createtime, tb_order.status, tb_order.staffnum, tb_order.cloumn7, tb_order.cloumn8, tb_order.cloumn9, tb_order.cloumn10, tb_order.cloumn11, tb_staff.staffname, tb_staff.logintime, tb_staff.synctime from tb_order LEFT OUTER JOIN tb_staff USING(staffnum) WHERE staffnum=123456782;
