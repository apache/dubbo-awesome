# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 5.854 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 9.285 ops/ms
Iteration   2: 9.217 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.328 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (9.217, 9.328, 9.482), stdev = 0.138
  CI (99.9%): [6.815, 11.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
# Warmup Iteration   2: 8.469 ops/ms
# Warmup Iteration   3: 9.559 ops/ms
Iteration   1: 9.750 ops/ms
Iteration   2: 9.552 ops/ms
Iteration   3: 9.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.707 ±(99.9%) 2.523 ops/ms [Average]
  (min, avg, max) = (9.552, 9.707, 9.819), stdev = 0.138
  CI (99.9%): [7.184, 12.230] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.891 ops/ms
# Warmup Iteration   2: 8.344 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.233 ops/ms
Iteration   2: 9.490 ops/ms
Iteration   3: 9.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.287 ±(99.9%) 3.327 ops/ms [Average]
  (min, avg, max) = (9.138, 9.287, 9.490), stdev = 0.182
  CI (99.9%): [5.960, 12.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.601 ops/ms
# Warmup Iteration   2: 7.230 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 7.415 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 7.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.723 ±(99.9%) 4.876 ops/ms [Average]
  (min, avg, max) = (7.415, 7.723, 7.892), stdev = 0.267
  CI (99.9%): [2.848, 12.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.185 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.005 ms/op
Iteration   1: 3.423 ±(99.9%) 0.007 ms/op
Iteration   2: 3.377 ±(99.9%) 0.005 ms/op
Iteration   3: 3.560 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (3.377, 3.453, 3.560), stdev = 0.095
  CI (99.9%): [1.721, 5.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.505 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.004 ms/op
Iteration   1: 3.258 ±(99.9%) 0.002 ms/op
Iteration   2: 3.218 ±(99.9%) 0.004 ms/op
Iteration   3: 3.271 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.218, 3.249, 3.271), stdev = 0.028
  CI (99.9%): [2.746, 3.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.399 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.007 ms/op
Iteration   1: 3.483 ±(99.9%) 0.005 ms/op
Iteration   2: 3.520 ±(99.9%) 0.007 ms/op
Iteration   3: 3.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.491 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (3.470, 3.491, 3.520), stdev = 0.026
  CI (99.9%): [3.018, 3.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.260 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.011 ms/op
Iteration   1: 4.242 ±(99.9%) 0.007 ms/op
Iteration   2: 4.127 ±(99.9%) 0.009 ms/op
Iteration   3: 4.064 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.145 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (4.064, 4.145, 4.242), stdev = 0.090
  CI (99.9%): [2.495, 5.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.370 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.012 ms/op
Iteration   1: 3.538 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.991 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  18.973 ms/op
                 createUser·p0.9999: 23.952 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.503 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.062 ms/op
                 createUser·p0.999:  10.870 ms/op
                 createUser·p0.9999: 22.261 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   3: 3.398 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   6.112 ms/op
                 createUser·p0.999:  22.815 ms/op
                 createUser·p0.9999: 57.606 ms/op
                 createUser·p1.00:   59.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276368
  mean =      3.479 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265687 
    [ 5.000, 10.000) = 10223 
    [10.000, 15.000) = 141 
    [15.000, 20.000) = 94 
    [20.000, 25.000) = 158 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     18.993 ms/op
     p(99.9900) =     56.128 ms/op
     p(99.9990) =     59.179 ms/op
     p(99.9999) =     59.179 ms/op
    p(100.0000) =     59.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.057 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.012 ms/op
Iteration   1: 3.342 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  19.162 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  12.720 ms/op
                 existUser·p0.9999: 26.042 ms/op
                 existUser·p1.00:   26.673 ms/op

Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  14.044 ms/op
                 existUser·p0.9999: 27.459 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285166
  mean =      3.366 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6666 
    [ 2.500,  5.000) = 269799 
    [ 5.000,  7.500) = 7322 
    [ 7.500, 10.000) = 905 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     28.054 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.503 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.817 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.010 ms/op
Iteration   1: 3.458 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.752 ms/op
                 getUser·p0.999:  18.728 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   2: 3.427 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 25.617 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 3.562 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.401 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  19.372 ms/op
                 getUser·p0.9999: 27.722 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275347
  mean =      3.481 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6770 
    [ 2.500,  5.000) = 258206 
    [ 5.000,  7.500) = 8638 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     26.474 ms/op
     p(99.9990) =     28.320 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.935 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.015 ms/op
Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.691 ms/op
                 listUser·p0.999:  20.103 ms/op
                 listUser·p0.9999: 23.809 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  14.751 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  14.826 ms/op
                 listUser·p0.9999: 19.890 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235758
  mean =      4.069 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 224373 
    [ 5.000,  7.500) = 8163 
    [ 7.500, 10.000) = 2286 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     22.376 ms/op
     p(99.9990) =     24.695 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.328 ± 2.513  ops/ms
ClientPb.existUser                       thrpt       3   9.707 ± 2.523  ops/ms
ClientPb.getUser                         thrpt       3   9.287 ± 3.327  ops/ms
ClientPb.listUser                        thrpt       3   7.723 ± 4.876  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 1.733   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 0.503   ms/op
ClientPb.getUser                          avgt       3   3.491 ± 0.472   ms/op
ClientPb.listUser                         avgt       3   4.145 ± 1.649   ms/op
ClientPb.createUser                     sample  276368   3.479 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.799           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.993           ms/op
ClientPb.createUser:createUser·p0.9999  sample          56.128           ms/op
ClientPb.createUser:createUser·p1.00    sample          59.179           ms/op
ClientPb.existUser                      sample  285166   3.366 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.232           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.783           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.714           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.411           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.246           ms/op
ClientPb.getUser                        sample  275347   3.481 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.401           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.682           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.474           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.475           ms/op
ClientPb.listUser                       sample  235758   4.069 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.286           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.004           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
