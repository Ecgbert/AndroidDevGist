import android.view.View;
import android.app.Activity;
import android.content.Context;
import android.os.Build;
import android.view.Window;
import android.view.WindowManager;

import androidx.core.content.ContextCompat;
    
    public class SystemUiTool {
    
        /**
         * 取得狀態欄高度
         */
        public static int getStatusBarHeight(Context context) {
            int statusBarHeight = 0;
            int resourceId = context.getResources().getIdentifier("status_bar_height", "dimen", "android");
            if (resourceId > 0) {
                statusBarHeight = context.getResources().getDimensionPixelSize(resourceId);
            }
            return statusBarHeight;
        }
        
        /**
         * 取得虛擬導航鍵高度
         */
        public static int getNavigationBarHeight(Context context) {
            int navigationBarHeight = 0;
            int rid = context.getResources().getIdentifier("config_showNavigationBar", "bool", "android");
            if (rid != 0) {
                int resourceId = context.getResources().getIdentifier("navigation_bar_height", "dimen", "android");
                navigationBarHeight = context.getResources().getDimensionPixelSize(resourceId);
            }
            return navigationBarHeight;
        }
    }
