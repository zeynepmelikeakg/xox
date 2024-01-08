# xox
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }
        string oyuncu = "X";
        int hamlesayisi = 0;
        private void label1_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label2_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
           
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label3_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label4_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label5_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label6_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label7_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
            
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label8_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
           
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        private void label9_Click(object sender, EventArgs e)
        {
            Label label = (Label)sender;
           
            label.Text = oyuncu;
            label.Enabled = false;
            if (oyuncu == "X")
            {
                oyuncu = "O";
            }
            else if (oyuncu == "O")
            { oyuncu = "X"; }
            hamlesayisi++;
            sonuc();
        }

        void sonuc()
        {
            if (label1.Text == "X" && label2.Text == "X" && label3.Text  == "X" ||
               label4.Text == "X" && label5.Text == "X" && label6.Text == "X" ||
               label7.Text == "X" && label8.Text == "X" && label9.Text == "X" ||
               label1.Text == "X" && label4.Text == "X" && label7.Text == "X" ||
               label2.Text == "X" && label5.Text == "X" && label8.Text == "X" ||
               label3.Text == "X" && label6.Text == "X" && label9.Text == "X" ||
               label1.Text == "X" && label5.Text == "X" && label9.Text == "X" ||
               label3.Text == "X" && label5.Text == "X" && label7.Text == "X")
            {
                MessageBox.Show("X kazandi");
                Close();
            }
            if (label1.Text == "O" && label2.Text == "O" && label3.Text == "O" ||
               label4.Text == "O" && label5.Text == "O" && label6.Text == "O" ||
               label7.Text == "O" && label8.Text == "O" && label9.Text == "O" ||
               label1.Text == "O" && label4.Text == "O" && label7.Text == "O" ||
               label2.Text == "O" && label5.Text == "O" && label8.Text == "O" ||
               label3.Text == "O" && label6.Text == "O" && label9.Text == "O" ||
               label1.Text == "O" && label5.Text == "O" && label9.Text == "O" ||
               label3.Text == "O" && label5.Text == "O" && label7.Text == "O")
            {
                MessageBox.Show("0 kazandi");
                Close();
            }
            if(hamlesayisi == 9)
            {
                MessageBox.Show("Berabere");
                Close();
            }
        }
    }
}
