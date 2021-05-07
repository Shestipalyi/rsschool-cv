# Resume

1. Andrei Isakov<br/>
2. shestipalyi@gmail.com<br/>
3. Designer of undergroud costructions
4. Skills: Java<br/>
5. Code examples:
public class Task2 {<br/>

	public static void main(String[] args) throws IOException {<br/>
		File file = new File("Result.txt");<br/>
		StringBuilder sb = new StringBuilder();<br/>		
		try (FileReader fr = new FileReader("Text.txt")) {<br/>
			int b;<br/>
			while ((b = fr.read()) != -1) {<br/>
				if (' ' != ((char) b)) {<br/>
					sb.append((char) b);<br/>
				}<br/>
			}<br/>
		} catch (IOException e) {<br/>
			System.out.println(e.getMessage());<br/>
		}<br/>
		try (FileWriter fw = new FileWriter(file);) {<br/>
			file.createNewFile();<br/>
			fw.write(sb.toString());<br/>
		} catch (IOException e) {<br/>
			System.out.println(e.getMessage());<br/>
		}<br/>
	}<br/>
}<br/>


6. No programming experience on a real project
7. Belarusian National Technical University, TRANSPORT COMMUNICATIONS FACULTY<br/>
8. English A2
