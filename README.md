# campus-car-rental
415-project 

campus-car-rental/
├── README.md *
├── .gitignore *
│
├── db/
│   ├── schema.sql           # table definitions (Postgres) *
│   └── policies.sql         # RLS policies, version-controlled *
│
└── mobile/
├── App.js
├── config.js            # Supabase URL + anon key
├── screens/             # same seven screens
├── components/          # same four components
├── api/
│   ├── client.js        # supabase.createClient()
│   ├── auth.js          # supabase.auth calls
│   ├── cars.js          # supabase.from('cars')
│   └── bookings.js      # supabase.from('bookings')
├── context/
│   └── AuthContext.js
├── utils/
│   └── availability.js  # the overlap check, now client-side
└── assets/images/