# How-To-Open-A-New-Jframe-On-Button-Click-In-Netbeans
How To Open A New Jframe On Button Click In Netbeans
For more details - http://mauricemuteti.info/how-to-open-a-new-jframe-on-button-click-in-netbeans/
Video Tutorial - https://www.youtube.com/watch?v=1VonIsK__V4
<pre>

	ViewSelectedRowJFrame viewSelectedRow = new ViewSelectedRowJFrame();
        viewSelectedRow.setVisible(true);
        //prevent the frame from closing the parent frame
        viewSelectedRow.setDefaultCloseOperation(JFrame.DISPOSE_ON_CLOSE);


</pre>
