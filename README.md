
        jLabel1 = new javax.swing.JLabel();
        buttonGroup1 = new javax.swing.ButtonGroup();
        buttonGroup2 = new javax.swing.ButtonGroup();
        rbBird = new javax.swing.JRadioButton();
        rbCat = new javax.swing.JRadioButton();
        rbDog = new javax.swing.JRadioButton();
        rbRabbit = new javax.swing.JRadioButton();
        rbPig = new javax.swing.JRadioButton();
        lblImage = new javax.swing.JLabel();

        jLabel1.setText("jLabel1");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);
        setTitle("Selecting  Pet");

        buttonGroup1.add(rbBird);
        rbBird.setText("Bird");
        rbBird.setToolTipText("");
        rbBird.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                rbBirdActionPerformed(evt);
            }
        });

        buttonGroup1.add(rbCat);
        rbCat.setText("Cat");
        rbCat.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                rbCatActionPerformed(evt);
            }
        });

        buttonGroup1.add(rbDog);
        rbDog.setText("Dog");
        rbDog.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                rbDogActionPerformed(evt);
            }
        });

        buttonGroup1.add(rbRabbit);
        rbRabbit.setText("Rabbit");
        rbRabbit.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                rbRabbitActionPerformed(evt);
            }
        });

        buttonGroup1.add(rbPig);
        rbPig.setText("Pig");
        rbPig.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                rbPigActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(rbDog)
                    .addComponent(rbRabbit)
                    .addComponent(rbPig)
                    .addComponent(rbCat)
                    .addComponent(rbBird))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, 46, Short.MAX_VALUE)
                .addComponent(lblImage, javax.swing.GroupLayout.PREFERRED_SIZE, 502, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addContainerGap())
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(rbBird)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(rbCat)
                .addGap(22, 22, 22)
                .addComponent(rbDog)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(rbRabbit)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(rbPig)
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
            .addGroup(layout.createSequentialGroup()
                .addComponent(lblImage, javax.swing.GroupLayout.PREFERRED_SIZE, 483, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addGap(0, 0, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void rbBirdActionPerformed(java.awt.event.ActionEvent evt) {                                       
        lblImage.setIcon(new javax.swing.ImageIcon(
        getClass().getResource("/Images/bird.png.jpeg")));

        javax.swing.JOptionPane.showMessageDialog(
        this,
        "You selected: Bird");      
    }                                      

    private void rbCatActionPerformed(java.awt.event.ActionEvent evt) {                                      
         lblImage.setIcon(new javax.swing.ImageIcon(
        getClass().getResource("/Images/cat.png.jpeg")));

        javax.swing.JOptionPane.showMessageDialog(
        this,
        "You selected: Cat"); 
    }                                     

    private void rbDogActionPerformed(java.awt.event.ActionEvent evt) {                                      
         lblImage.setIcon(new javax.swing.ImageIcon(
        getClass().getResource("/Images/dog.png.jpeg")));

        javax.swing.JOptionPane.showMessageDialog(
        this,
        "You selected: Dog"); 
    }                                     

    private void rbRabbitActionPerformed(java.awt.event.ActionEvent evt) {                                         
         lblImage.setIcon(new javax.swing.ImageIcon(
        getClass().getResource("/Images/rabbit.png.jpeg")));

        javax.swing.JOptionPane.showMessageDialog(
        this,
        "You selected: Rabbit"); 
    }                                        

    private void rbPigActionPerformed(java.awt.event.ActionEvent evt) {                                      
         lblImage.setIcon(new javax.swing.ImageIcon(
        getClass().getResource("/Images/pig.png.jpeg")));

        javax.swing.JOptionPane.showMessageDialog(
        this,
        "You selected: Pig"); 
    }  
