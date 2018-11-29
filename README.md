# NeelLeisureTravel
private void btnCALCULATE_Click(object sender, EventArgs e)
        {
            //object is created of type addition
            Addition addition = new Addition();
            //Result is added into list box
            NeelListBox.Items.Add(addition.Sum(10, 20).ToString());
            NeelListBox.Items.Add(addition.Sum(10, 15.7F).ToString());
            NeelListBox.Items.Add(addition.Sum(10, 20, 30).ToString());
        }
