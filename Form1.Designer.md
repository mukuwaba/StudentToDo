           namespace StudentTodo
{
    partial class Form1
    {
        /// <summary>
        ///  Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        ///  Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        ///  Required method for Designer support - do not modify
        ///  the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            components = new System.ComponentModel.Container();
            Submit_Button = new Button();
            Cancel_Button = new Button();
            textBox1 = new TextBox();
            AddTask = new Label();
            textBox2 = new TextBox();
            textBox3 = new TextBox();
            textBox4 = new TextBox();
            notifyIcon1 = new NotifyIcon(components);
            notifyIcon2 = new NotifyIcon(components);
            UserPrompt = new Label();
            textBox5 = new TextBox();
            label1 = new Label();
            textBox6 = new TextBox();
            textBox7 = new TextBox();
            textBox8 = new TextBox();
            SuspendLayout();
            // 
            // Submit_Button
            // 
            Submit_Button.BackColor = SystemColors.ScrollBar;
            Submit_Button.Location = new Point(433, 386);
            Submit_Button.Name = "Submit_Button";
            Submit_Button.Size = new Size(131, 40);
            Submit_Button.TabIndex = 0;
            Submit_Button.Text = "Submit";
            Submit_Button.UseVisualStyleBackColor = false;
            Submit_Button.Click += button1_Click;
            // 
            // Cancel_Button
            // 
            Cancel_Button.BackColor = SystemColors.ScrollBar;
            Cancel_Button.Location = new Point(178, 386);
            Cancel_Button.Name = "Cancel_Button";
            Cancel_Button.Size = new Size(131, 40);
            Cancel_Button.TabIndex = 1;
            Cancel_Button.Text = "Cancel";
            Cancel_Button.UseVisualStyleBackColor = false;
            Cancel_Button.Click += Cancel_Button_Click;
            // 
            // textBox1
            // 
            textBox1.Location = new Point(75, 121);
            textBox1.Name = "textBox1";
            textBox1.Size = new Size(175, 35);
            textBox1.TabIndex = 2;
            textBox1.TextChanged += textBox1_TextChanged;
            // 
            // AddTask
            // 
            AddTask.AutoSize = true;
            AddTask.Location = new Point(75, 88);
            AddTask.Name = "AddTask";
            AddTask.Size = new Size(117, 30);
            AddTask.TabIndex = 3;
            AddTask.Text = "Add Task(s)";
            AddTask.Click += label1_Click;
            // 
            // textBox2
            // 
            textBox2.Location = new Point(75, 173);
            textBox2.Name = "textBox2";
            textBox2.Size = new Size(175, 35);
            textBox2.TabIndex = 4;
            // 
            // textBox3
            // 
            textBox3.Location = new Point(75, 233);
            textBox3.Name = "textBox3";
            textBox3.Size = new Size(175, 35);
            textBox3.TabIndex = 5;
            // 
            // textBox4
            // 
            textBox4.Location = new Point(75, 293);
            textBox4.Name = "textBox4";
            textBox4.Size = new Size(175, 35);
            textBox4.TabIndex = 6;
            // 
            // notifyIcon1
            // 
            notifyIcon1.Text = "notifyIcon1";
            notifyIcon1.Visible = true;
            // 
            // notifyIcon2
            // 
            notifyIcon2.Text = "notifyIcon2";
            notifyIcon2.Visible = true;
            // 
            // UserPrompt
            // 
            UserPrompt.AutoSize = true;
            UserPrompt.Location = new Point(75, 41);
            UserPrompt.Name = "UserPrompt";
            UserPrompt.Size = new Size(363, 30);
            UserPrompt.TabIndex = 7;
            UserPrompt.Text = "Please enter tasks in the boxes below.";
            // 
            // textBox5
            // 
            textBox5.Location = new Point(324, 121);
            textBox5.Name = "textBox5";
            textBox5.Size = new Size(175, 35);
            textBox5.TabIndex = 8;
            textBox5.TextChanged += textBox5_TextChanged;
            // 
            // label1
            // 
            label1.AutoSize = true;
            label1.Location = new Point(324, 88);
            label1.Name = "label1";
            label1.Size = new Size(257, 30);
            label1.TabIndex = 9;
            label1.Text = "Priority (HIGH, MED, LOW)";
            label1.Click += label1_Click_1;
            // 
            // textBox6
            // 
            textBox6.Location = new Point(324, 173);
            textBox6.Name = "textBox6";
            textBox6.Size = new Size(175, 35);
            textBox6.TabIndex = 10;
            // 
            // textBox7
            // 
            textBox7.Location = new Point(324, 233);
            textBox7.Name = "textBox7";
            textBox7.Size = new Size(175, 35);
            textBox7.TabIndex = 11;
            // 
            // textBox8
            // 
            textBox8.Location = new Point(324, 293);
            textBox8.Name = "textBox8";
            textBox8.Size = new Size(175, 35);
            textBox8.TabIndex = 12;
            // 
            // Form1
            // 
            AutoScaleDimensions = new SizeF(12F, 30F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(800, 450);
            Controls.Add(textBox8);
            Controls.Add(textBox7);
            Controls.Add(textBox6);
            Controls.Add(label1);
            Controls.Add(textBox5);
            Controls.Add(UserPrompt);
            Controls.Add(textBox4);
            Controls.Add(textBox3);
            Controls.Add(textBox2);
            Controls.Add(AddTask);
            Controls.Add(textBox1);
            Controls.Add(Cancel_Button);
            Controls.Add(Submit_Button);
            Name = "Form1";
            Text = "Form1";
            Load += Form1_Load;
            ResumeLayout(false);
            PerformLayout();
        }

        #endregion

        private Button Submit_Button;
        private Button Cancel_Button;
        private TextBox textBox1;
        private Label AddTask;
        private TextBox textBox2;
        private TextBox textBox3;
        private TextBox textBox4;
        private NotifyIcon notifyIcon1;
        private NotifyIcon notifyIcon2;
        private Label UserPrompt;
        private TextBox textBox5;
        private Label label1;
        private TextBox textBox6;
        private TextBox textBox7;
        private TextBox textBox8;
    }
}
