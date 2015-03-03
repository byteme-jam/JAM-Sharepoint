# JAM-Sharepoint
This is our code for sharepoint

/**
 * Your application code goes here
 */

package userclasses;

//import java.net.*;

import generated.StateMachineBase;

import com.codename1.ui.*; 
import com.codename1.ui.Component;
import com.codename1.ui.Dialog;
import com.codename1.ui.events.*;
import com.codename1.ui.layouts.BorderLayout;
import com.codename1.ui.util.Resources;
/**
 *
 * @author Your name here
 */
public class StateMachine extends StateMachineBase {
    public StateMachine(String resFile) {
        super(resFile);
        // do not modify, write code in initVars and initialize class members there,
        // the constructor might be invoked too late due to race conditions that might occur
    }
    
    /**
     * this method should be used to initialize variables instead of
     * the constructor/class scope to avoid race conditions
     */
	/*protected void initVars(Resources res){
	}

    @Override
    protected void beforeHomePage(Form f) {
    
    }

    @Override
    protected void onLoginPage_LoginAction(Component c, ActionEvent event) {

    
    }

    @Override
    protected void onMain_MultiListAction(Component c, ActionEvent event) {

    
    }

    @Override
    protected void onMain_LogoutButtonAction(Component c, ActionEvent event) {

    
    }


    @Override
    protected void onMain_TeachersAction(Component c, ActionEvent event) {

    
    }


    @Override
    protected void onMain_ResourcesAction(Component c, ActionEvent event) {
    	
    
    }

  
*/
    
    
    protected void onResources_ButtonAction(Component c, ActionEvent event) {
    
    	
    	super.onResources_ButtonAction(c, event);
    	Dialog.show("Click the link","http://www.holynames-sea.org/", "Done", null);
    }
   
  
    
    protected void onResources_Button1Action(Component c, ActionEvent event) {
    	super.onResources_ButtonAction(c, event);
    	Dialog.show("Click the link","https://sms.holynames-sea.org/guardian/home.html", "Done", null);
    
    }

    
    protected void onResources_Button2Action(Component c, ActionEvent event) {
    	super.onResources_ButtonAction(c, event);
    	Dialog.show("Click the link","https://holynamesseattle-my.sharepoint.com", "Done", null);
    
    }
}
    

    
    	
  
 


