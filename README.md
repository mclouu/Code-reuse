# Code-reuse

# SwipeDirectionListener
Add this code in your activity who swipe

    public void swipe() {
        layout = findViewById(R.id.main_activity_layout);
        layout.setOnTouchListener(new SwipeDirectionListener(MainActivity.this) {

            public void onUpSwipe() {
              
			// CODE WHEN I UP SWIPE
			   
            }

            public void onDownSwipe() {

			// CODE WHEN I DOWN SWIPE
			
            }

        });


    }
