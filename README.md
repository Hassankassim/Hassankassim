<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/benjamin-maziku-mashimba-553b06247/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
<a href="https://www.instagram.com/_b.e.nn.y_/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge"/>
</a>
<a href="https://x.com/maziku_ben">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
</a>

</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=benny-png&style=plastic" alt="Profile Views"/>
  <img src="https://img.shields.io/github/followers/benny-png?style=social&label=Followers&maxAge=2592000" alt="GitHub Followers"/>
</div>

# Hi there 👋

My name is Benjamin 🎉 and I am a Computer Engineer 👨‍💻 by education, Software Developer and scientist by passion 🙂.

I got into tech and science from an anime scene, where a computer engineer was coding and repairing a time machine ⏳ in C and doing some robotics 🤖 back in 2018.


Looking forward to entering the Startup Space.

![GitHub Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=benny-png&theme=tokyo-night&hide_border=true&hide_title=false&area=true&custom_title=Total%20contribution%20graph%20in%20all%20repo)


- 🔭 I’m currently working on integrating Python into robotics
- 🌱 I’m currently learning firmware programming, Q#, Qiskit, assembly, Java & blender.
- 👯 I’m looking to collaborate on ML projects using C and 🐉
- 🤔 I’m looking for help with firmware & assembly programming
- 💬 Ask me about technology and scientists
- 😄 Pronouns: He/Him
- ⚡ Fun fact: I commit with spaces... and got rejected by all the Ivies

I'm an Explorer 🙂...
💡 Currently, I'm always learning, always creating, always improving!

## Languages 

<p align="center">
  <a href="https://www.python.org" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="55"/>
  </a>
  &nbsp;
  <a href="https://www.cplusplus.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/c-plus-plus-logo.png" alt="c++" width="55" height="55"/>
  </a>
  &nbsp;
  <a href="https://www.java.com" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="55" height="55"/>
  </a>
  &nbsp;
  <a href="https://www.cprogramming.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="55" height="55"/>
  </a>
</p>

## Frameworks & Tools

<p align="center">
  <a href="https://huggingface.co/" target="_blank">
    <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="hugging face" width="40" height="40"/>
  </a>
 &nbsp;
  <a href="https://visualstudio.microsoft.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/visual-studio.png" alt="Microsoft Visual Studio"/>
  </a>
  &nbsp;
  <a href="https://code.visualstudio.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/visual-studio-code-2019.png" alt="VS Code"/>
  </a>
  &nbsp;
   <a href="https://www.tensorflow.org/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="tensorflow"/>
  </a>
  &nbsp;
   <a href="https://opencv.org/" target="_blank">
<img src="https://github.com/devicons/devicon/blob/master/icons/opencv/opencv-original.svg" title="mpl" alt="mpl" width="40" height="40"/>
   </a>
  &nbsp;
  <a href="https://azure.microsoft.com/en-us/" target="_blank">
    <img src="https://img.icons8.com/fluency/48/azure-1.png" alt="azure"/>
  </a>
  &nbsp;```markdown
# FastAPI Project

A FastAPI application for managing contact buckets with admin functionalities, contact management, and vCard export.

## Project Structure

```plaintext
fastapi_project/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── config.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── bucket.py
│   ├── schemas/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── bucket.py
│   ├── routes/
│   │   ├── __init__.py
│   │   ├── auth.py
│   │   ├── admin.py
│   │   ├── user.py
│   ├── utils/
│   │   ├── __init__.py
│   │   ├── security.py
│   │   ├── vcard.py
│   └── db.py
└── .env
```

## Features

- **Admin Registration**: Register new admins with unique credentials.
- **Authentication**: Secure login with JWT token-based authentication.
- **Bucket Management**: Create and manage contact buckets with an optional contact name suffix.
- **Contact Management**: Manage and specify contact details in buckets.
- **vCard Export**: Download contact data in vCard format.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Configuration

1. **Create a `.env` File**

   Create a `.env` file in the root directory with the following content:

   ```env
   MONGODB_URL=your_mongodb_connection_url
   ADMIN_SECRET=your_admin_secret_key
   SECRET_KEY=your_jwt_secret_key
   ```

2. **Set Up Environment Variables**

   Ensure the `.env` file contains the necessary environment variables for MongoDB, admin secret, and JWT secret.

## API Endpoints

### Admin Registration

**POST /admin/register**

Registers a new admin.

**Request Body:**

```json
{
  "name": "string",
  "email": "string",
  "contact": "string",
  "password": "string"
}
```

**Headers:**

- `admin_secret`: The secret key for admin registration.

### Login

**POST /login**

Authenticates a user and returns a JWT token.

**Request Body:**

```json
{
  "username": "string",
  "password": "string"
}
```

**Response:**

```json
{
  "access_token": "string",
  "token_type": "bearer"
}
```

### Create Bucket

**POST /admin/create-bucket/**

Creates a new bucket with contacts and an optional suffix for contact names.

**Request Body:**

```json
{
  "name": "string",
  "contact_suffix": "string",
  "contacts": [
    {
      "name": "string",
      "phone_number": "string"
    }
  ]
}
```

**Headers:**

- `Authorization`: `Bearer <token>`

### Edit Bucket

**PUT /admin/edit-bucket/{bucket_id}**

Edits an existing bucket.

**Request Body:**

```json
{
  "name": "string",
  "contacts": [
    {
      "name": "string",
      "phone_number": "string"
    }
  ]
}
```

**Headers:**

- `Authorization`: `Bearer <token>`

### Download vCard

**GET /user/download-vcf/{bucket_id}**

Downloads contacts in vCard format.

**Headers:**

- `Authorization`: `Bearer <token>`

## Development

### Running Tests

Run the test suite with:

```bash
pytest
```

### Code Formatting

Format your code with:

```bash
black .
```

### Linting

Lint your code with:

```bash
pylint .
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- FastAPI
- Pydantic
- PassLib
- PyMongo
- JWT
- dotenv

For any issues or feature requests, please open an issue on the [GitHub repository](https://github.com/your-username/your-repository/issues).
```

  <a href="https://aws.amazon.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/amazon-web-services.png" alt="aws"/>
  </a>
  &nbsp;
  <a href="https://console.cloud.google.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/google-cloud.png" alt="google cloud"/>
  </a>
  &nbsp;
  <a href="https://www.mysql.com/" target="_blank">
    <img src="https://img.icons8.com/fluent/50/000000/mysql-logo.png" alt="mysql"/>
  </a>
  &nbsp;
  <a href="https://www.linux.org/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/linux.png" alt="linux"/>
  </a>
  &nbsp;
  <a href="https://www.arduino.cc/" target="_blank">
    <img src="https://img.icons8.com/color/48/fff/arduino.png" alt="arduino"/>
  </a>
  &nbsp;
  <a href="https://git-scm.com/" target="_blank">
    <img src="https://img.icons8.com/color/48/fff/git.png" alt="git"/>
  </a>
  &nbsp;
    <a href="https://ultralytics.com/yolov5" target="_blank">
    <img src="https://img.icons8.com/fluency/48/000000/artificial-intelligence.png" alt="yolo"/>
  </a>
  &nbsp;
    <a href="https://pytorch.org/" target="_blank">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/pytorch.svg" alt="pytorch" width="40" height="40"/>
  </a>
  <a href="https://www.shellscript.sh/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/console.png" alt="shell script"/>
  </a>
  &nbsp;
  <a href="https://www.qt.io/" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Qt_logo_2016.svg" alt="qt" width="40" height="40"/>
  </a>
</p>



## My Github Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=benny-png&theme=radical" alt="GitHub Streak"/>
  <img src="https://github-readme-stats.vercel.app/api?username=benny-png&show_icons=true&theme=radical" alt="Benjamin's GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=benny-png&layout=compact&theme=radical" alt="Top Languages"/>
</p>

## ME AT UDSM 3D ROBOTICS COMMUNITY

<p align="center">
  <img src="https://github.com/benny-png/benny-png/blob/main/WhatsApp%20Image%202024-06-25%20at%2011.05.07%20PM.jpeg" alt="ME AT UDSM ROBOTICS COMMUNITY">
</p>

## Connect with me

<p align="center">
  <a href="https://api.whatsapp.com/send/?phone=255627156369&text&app_absent=0" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/whatsapp.png" alt="WhatsApp"/>
  </a>
  <a href="https://www.linkedin.com/in/benjamin-maziku-mashimba-553b06247/" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="LinkedIn"/>
  </a>
  <a href="https://x.com/maziku_ben" target="_blank">
    <img src="https://img.icons8.com/fluency/48/000000/twitter.png" alt="Twitter"/>
  </a>
  <a href="https://instagram.com/_b.e.nn.y_/" target="_blank">
    <img src="https://img.icons8.com/fluency/48/000000/instagram-new.png" alt="Instagram"/>
  </a>
  <a href="https://www.facebook.com/" target="_blank">
    <img src="https://img.icons8.com/fluency/48/000000/facebook-new.png" alt="Facebook"/>
  </a>
  <a href="https://join.slack.com/t/frontendmentor/shared_invite/zt-12n9c8i9i-k0VAj7WkurceDTMppk1hAw" target="_blank">
    <img src="https://img.icons8.com/color/48/000000/slack-new.png" alt="Slack"/>
  </a>
</p>

<p align="center">
 <img width="1000" src="assets/github-snake.svg" alt="snake"/>
</p>


