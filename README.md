# 201601716 2.Hafta Ödevi 15/10/2021
<h2>Ödevin açıklaması</h2>
<h3>2. Hafta Ödevini bu alana pdf şeklinde yükleyiniz. Yazacağınız rapor 1-2 sayfalık bir özet olabilir. Konunun ne işe yaradığı ve amacıyla ilgili kısa bir bilgi yeterlidir. Diğer haftalarda takip eden haftanın ödevini yapmalısınız.</h3>

![ss](https://user-images.githubusercontent.com/76546216/137513298-1375cbc4-0001-43ee-8e1e-1c626d9e7c4e.PNG)

        

        }

        private void label2_Click(object sender, EventArgs e)
        {

        }

        private void checkBox1_CheckedChanged(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            double fiyat = Convert.ToDouble(textBox1.Text);
  
            if (checkBox1.Checked)
                textBox2.Text = (fiyat + fiyat * 0.18).ToString();
            else
                
            if (checkBox2.Checked)
                textBox2.Text = (fiyat - (fiyat * 0.05)).ToString();
            else
                textBox2.Text = fiyat.ToString();
         
        }

    private void checkBox2_CheckedChanged(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBox2_TextChanged(object sender, EventArgs e)
        {

        }
    }
}

[2Haftaödevi.zip](https://github.com/MoayadAlnada/2.haftaodevi/files/7354311/2Haftaodevi.zip)
