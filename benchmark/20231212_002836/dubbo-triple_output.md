# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ops/ms
# Warmup Iteration   2: 11.895 ops/ms
# Warmup Iteration   3: 12.195 ops/ms
Iteration   1: 12.461 ops/ms
Iteration   2: 12.700 ops/ms
Iteration   3: 12.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.553 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (12.461, 12.553, 12.700), stdev = 0.128
  CI (99.9%): [10.213, 14.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.887 ops/ms
# Warmup Iteration   2: 13.126 ops/ms
# Warmup Iteration   3: 13.065 ops/ms
Iteration   1: 12.935 ops/ms
Iteration   2: 13.255 ops/ms
Iteration   3: 13.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.139 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (12.935, 13.139, 13.255), stdev = 0.177
  CI (99.9%): [9.903, 16.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.573 ops/ms
# Warmup Iteration   2: 12.917 ops/ms
# Warmup Iteration   3: 13.285 ops/ms
Iteration   1: 13.130 ops/ms
Iteration   2: 12.985 ops/ms
Iteration   3: 13.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.176 ±(99.9%) 3.962 ops/ms [Average]
  (min, avg, max) = (12.985, 13.176, 13.412), stdev = 0.217
  CI (99.9%): [9.214, 17.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.780 ops/ms
# Warmup Iteration   2: 10.477 ops/ms
# Warmup Iteration   3: 10.713 ops/ms
Iteration   1: 10.937 ops/ms
Iteration   2: 10.890 ops/ms
Iteration   3: 10.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.903 ±(99.9%) 0.533 ops/ms [Average]
  (min, avg, max) = (10.883, 10.903, 10.937), stdev = 0.029
  CI (99.9%): [10.371, 11.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.938 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.447 ±(99.9%) 0.003 ms/op
Iteration   3: 2.436 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.441 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.436, 2.441, 2.447), stdev = 0.005
  CI (99.9%): [2.345, 2.538] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.389 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.379 ±(99.9%) 0.003 ms/op
Iteration   1: 2.337 ±(99.9%) 0.004 ms/op
Iteration   2: 2.359 ±(99.9%) 0.003 ms/op
Iteration   3: 2.333 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.343 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.333, 2.343, 2.359), stdev = 0.014
  CI (99.9%): [2.087, 2.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.003 ms/op
Iteration   1: 2.424 ±(99.9%) 0.004 ms/op
Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
Iteration   3: 2.415 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.416 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (2.408, 2.416, 2.424), stdev = 0.008
  CI (99.9%): [2.268, 2.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.528 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.004 ms/op
Iteration   1: 2.967 ±(99.9%) 0.005 ms/op
Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
Iteration   3: 2.976 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.975 ±(99.9%) 0.121 ms/op [Average]
  (min, avg, max) = (2.967, 2.975, 2.980), stdev = 0.007
  CI (99.9%): [2.854, 3.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.104 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.621 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  7.852 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.559 ms/op
                 createUser·p0.999:  10.868 ms/op
                 createUser·p0.9999: 12.466 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  7.811 ms/op
                 createUser·p0.9999: 9.814 ms/op
                 createUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 390687
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 192524 
    [ 2.500,  3.750) = 194493 
    [ 3.750,  5.000) = 2782 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 175 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     13.784 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.509 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.362 ±(99.9%) 0.005 ms/op
Iteration   1: 2.363 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.652 ms/op
                 existUser·p0.9999: 13.614 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.377 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.429 ms/op
                 existUser·p0.90:   2.896 ms/op
                 existUser·p0.95:   2.998 ms/op
                 existUser·p0.99:   3.445 ms/op
                 existUser·p0.999:  5.222 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.536 ms/op
                 existUser·p0.9999: 11.364 ms/op
                 existUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 401844
  mean =      2.387 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 208730 
    [ 2.500,  3.750) = 190348 
    [ 3.750,  5.000) = 2091 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =      5.652 ms/op
     p(99.9900) =     13.134 ms/op
     p(99.9990) =     13.942 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.006 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.933 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  5.855 ms/op
                 getUser·p0.9999: 13.348 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  6.256 ms/op
                 getUser·p0.9999: 12.411 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.397 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   2.912 ms/op
                 getUser·p0.95:   3.043 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  5.864 ms/op
                 getUser·p0.9999: 21.996 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 398664
  mean =      2.406 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206111 
    [ 2.500,  5.000) = 191676 
    [ 5.000,  7.500) = 493 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =     13.669 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.699 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.008 ms/op
Iteration   1: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.910 ms/op
                 listUser·p0.9999: 10.014 ms/op
                 listUser·p1.00:   10.764 ms/op

Iteration   2: 2.967 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 11.108 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   3: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 10.355 ms/op
                 listUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324308
  mean =      2.957 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 103626 
    [ 2.500,  3.750) = 183621 
    [ 3.750,  5.000) = 29310 
    [ 5.000,  6.250) = 6290 
    [ 6.250,  7.500) = 606 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 340 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     10.643 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.553 ± 2.340  ops/ms
ClientPb.existUser                       thrpt       3  13.139 ± 3.236  ops/ms
ClientPb.getUser                         thrpt       3  13.176 ± 3.962  ops/ms
ClientPb.listUser                        thrpt       3  10.903 ± 0.533  ops/ms
ClientPb.createUser                       avgt       3   2.441 ± 0.096   ms/op
ClientPb.existUser                        avgt       3   2.343 ± 0.256   ms/op
ClientPb.getUser                          avgt       3   2.416 ± 0.148   ms/op
ClientPb.listUser                         avgt       3   2.975 ± 0.121   ms/op
ClientPb.createUser                     sample  390687   2.455 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.599           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.527           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.982           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.602           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.861           ms/op
ClientPb.existUser                      sample  401844   2.387 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.645           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.441           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.904           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.652           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.134           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  398664   2.406 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.803           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.929           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.210           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.669           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.446           ms/op
ClientPb.listUser                       sample  324308   2.957 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.643           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.009           ms/op
