<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coding Languages Blog & Learning</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }

        main {
            padding: 2rem;
        }

        .language-post {
            margin-bottom: 2rem;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
        }

        .language-post h3 {
            color: #333;
        }

        .language-post p {
            line-height: 1.6;
        }

        .example-code {
            background-color: #f5f5f5;
            padding: 1rem;
            border-radius: 8px;
            margin-top: 1rem;
            position: relative;
        }

        .copy-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #333;
            color: white;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 4px;
        }

        .copy-btn:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        pre {
            font-family: "Courier New", Courier, monospace;
            white-space: pre-wrap;
            word-wrap: break-word;
        }

    </style>
</head>

<body>

    <header>
        <h1>Coding Languages Blog & Learning Platform</h1>
        <p>Explore and learn programming languages with detailed explanations and examples.</p>
    </header>

    <main>
        <div class="language-post">
            <h3>1. JavaScript</h3>
            <p>JavaScript is a versatile, high-level programming language used primarily for web development. It allows you to create interactive web pages, dynamic content, and server-side programming.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('js-example')">Copy</button>
                <pre id="js-example">
console.log("Hello, World!");
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>2. Python</h3>
            <p>Python is a high-level, interpreted language known for its simplicity and readability. It’s widely used in web development, data science, and artificial intelligence.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('python-example')">Copy</button>
                <pre id="python-example">
print("Hello, World!")
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>3. Java</h3>
            <p>Java is a popular object-oriented programming language that can be used to create cross-platform applications, web applications, and more. It's known for its portability and security.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('java-example')">Copy</button>
                <pre id="java-example">
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>4. Ruby</h3>
            <p>Ruby is a dynamic, open-source programming language focused on simplicity and productivity. It’s known for being used with the Ruby on Rails framework to build web applications.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('ruby-example')">Copy</button>
                <pre id="ruby-example">
puts "Hello, World!"
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>5. Go</h3>
            <p>Go (or Golang) is a statically typed, compiled language designed by Google. It's known for its speed and efficiency in building scalable web services, cloud computing, and large-scale systems.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('go-example')">Copy</button>
                <pre id="go-example">
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>6. C++</h3>
            <p>C++ is a powerful, high-performance language used in system programming, game development, and software requiring low-level memory manipulation.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('cpp-example')">Copy</button>
                <pre id="cpp-example">
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!" << endl;
    return 0;
}
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>7. Swift</h3>
            <p>Swift is a fast and interactive programming language developed by Apple for iOS, macOS, and watchOS app development. It focuses on performance and safety.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('swift-example')">Copy</button>
                <pre id="swift-example">
import Swift

print("Hello, World!")
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>8. PHP</h3>
            <p>PHP is a widely-used, open-source scripting language suited for web development. It is commonly embedded in HTML to create dynamic web pages.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('php-example')">Copy</button>
                <pre id="php-example">
<?php
echo "Hello, World!";
?>
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>9. Rust</h3>
            <p>Rust is a systems programming language that emphasizes memory safety without sacrificing performance. It's commonly used in game engines, operating systems, and web assembly.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('rust-example')">Copy</button>
                <pre id="rust-example">
fn main() {
    println!("Hello, World!");
}
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>10. TypeScript</h3>
            <p>TypeScript is a superset of JavaScript that adds static typing. It's used to build large-scale applications and helps catch errors during development.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('typescript-example')">Copy</button>
                <pre id="typescript-example">
console.log("Hello, World!");
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>11. Perl</h3>
            <p>Perl is a high-level language known for its text-processing capabilities. It’s used in web development, network programming, and bioinformatics.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('perl-example')">Copy</button>
                <pre id="perl-example">
print "Hello, World!\n";
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>12. Haskell</h3>
            <p>Haskell is a purely functional programming language known for its strong type system and mathematical foundations. It is widely used in academia and research.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('haskell-example')">Copy</button>
                <pre id="haskell-example">
main = putStrLn "Hello, World!"
                </pre>
            </div>
        </div>
        <div class="language-post">
            <h3>13. Kotlin</h3>
            <p>Kotlin is a statically typed language that runs on the JVM and is fully interoperable with Java. It's the official language for Android development.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('kotlin-example')">Copy</button>
                <pre id="kotlin-example">
fun main() {
    println("Hello, World!")
}
                </pre>
            </div>
        </div>

        <div class="language-post">
            <h3>14. Dart</h3>
            <p>Dart is a programming language optimized for building mobile, desktop, and web applications. It is the primary language used in the Flutter framework for building cross-platform mobile apps.</p>
            <div class="example-code">
                <button class="copy-btn" onclick="copyToClipboard('dart-example')">Copy</button>
                <pre id="dart-example">
void main() {
  print("Hello, World!");
}
                </pre>
            </div>
        </div>

    </main>

    <footer>
        <p>&copy; 2024 Coding Languages Blog | Learn programming in different languages.</p>
    </footer>

    <script>
        // Function to copy code to clipboard
        function copyToClipboard(codeId) {
            const code = document.getElementById(codeId).textContent || document.getElementById(codeId).innerText;
            const textArea = document.createElement("textarea");
            textArea.value = code;
            document.body.appendChild(textArea);
            textArea.select();
            document.execCommand('copy');
            document.body.removeChild(textArea);

            alert("Code copied to clipboard!");
        }
    </script>

</bod>
</html>
