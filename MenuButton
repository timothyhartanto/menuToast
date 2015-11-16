package com.example.proto.menubutton;

import android.app.Activity;
import android.content.Intent;
import android.os.Bundle;
import android.view.Menu;
import android.view.MenuItem;
import android.view.MenuInflater;
import android.widget.Toast;

public class MenuButton extends Activity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_menu_item);
    }

    public boolean onCreateOptionsMenu(Menu menu){
        super.onCreateOptionsMenu(menu);
        MenuInflater inflater = getMenuInflater();
        inflater.inflate(R.menu.main_menu, menu);
        return true;
    }

    public boolean onOptionsItemSelected(MenuItem item){
        switch(item.getItemId()){
            case R.id.menuID:
                startActivity(new Intent("com.example.proto.menubutton.STARTMENU"));
                return true;
            case R.id.secondMenu:
                Toast something = Toast.makeText(MenuButton.this, "This is a toast", Toast.LENGTH_LONG);
                something.show();
                return true;
        }
        return false;
    }
}
