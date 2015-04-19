# MultiCardMenu
 A card menu that can open and close with animation on android.It base on nineoldandroid ,thank about it.

## Demo

   <img src="./multi_card_menu_demo_static.png"  width="401" heigit="638" alt="Screenshot"/>


####Warning:The childview not support Listview,Scrollview...now!
<br/>
<p>
   <img src="./multi_card_menu_demo.gif"  width="401" heigit="638" alt="Screenshot"/>
</p>

<br/>

##Usage
	
	   <net.wujingchao.android.view.MultiCardMenu
	        xmlns:simple="http://schemas.android.com/apk/res-auto"
	        android:id="@+id/multi_card_menu"
	        android:layout_width="match_parent"
	        android:layout_height="match_parent"
	        simple:background_layout="@layout/background_view"
	        simple:margin_top="50dp"
	        simple:fade="true"
	        simple:title_bar_height_display="20dp"
	        simple:title_bar_height_no_display="60dp"
	        simple:boundary="true"
			simple:move_distance_to_trigger="30dip"
			simple:animator_duration="300">

				....(Your ChildViews)

	   </net.wujingchao.android.view.MultiCardMenu>
	
### Quick Start

Just import it to your project as a module in Android Studio.


######You can mail me => wujingchao@aliyun.com




License
-------

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
