1---C#窗体常用控件与方法

	---维护原因
	
	小白进行窗体设计，常遇到问题：
	1.不知道控件含义
	2.不知道控件常用方法
	
	---维护主体
	
	▣容器：groupBox
	▢：CheckBox
	◯：RadioButton	
	
	选中方法：if (c is CheckBox && ((CheckBox)c).Checked == true)
	遍历groupBox容器选中的控件：
	foreach (Control b in groupBox2.Controls)
            {
                if (b is RadioButton && ((RadioButton)b).Checked == true)
                {
                    // count2 = Convert.ToInt32(b.Text);
                }
            }	
			
	---维护主体
1---C#窗体常用控件与方法

	---维护原因
	
	小白进行窗体设计，常遇到问题：
	1.不知道控件含义
	2.不知道控件常用方法
	
	---维护主体
	
	▣容器：groupBox
	▢：CheckBox
	◯：RadioButton	
	
	选中方法：if (c is CheckBox && ((CheckBox)c).Checked == true)
	遍历groupBox容器选中的控件：
	foreach (Control b in groupBox2.Controls)
            {
                if (b is RadioButton && ((RadioButton)b).Checked == true)
                {
                    // count2 = Convert.ToInt32(b.Text);
                }
            }	
			
	---维护主体
