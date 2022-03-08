

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        EditText Number1 = findViewById(R.id.edittext1) ;
        EditText Number2 = findViewById(R.id.edittext2) ;
        Button cal = findViewById(R.id.button) ;
        TextView result = findViewById(R.id.total) ;
        cal.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                int firstNumber = Integer.parseInt(Number1.getText().toString()) ;
                int secondNumber = Integer.parseInt(Number2.getText().toString()) ;
                int total = firstNumber + secondNumber ;
                result.setText(total + "");

            }
        });


    }
}