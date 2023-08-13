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
# Warmup Iteration   1: 1.673 ops/ms
# Warmup Iteration   2: 3.763 ops/ms
# Warmup Iteration   3: 7.276 ops/ms
Iteration   1: 7.549 ops/ms
Iteration   2: 8.094 ops/ms
Iteration   3: 7.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.825 ±(99.9%) 4.980 ops/ms [Average]
  (min, avg, max) = (7.549, 7.825, 8.094), stdev = 0.273
  CI (99.9%): [2.845, 12.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 8.201 ops/ms
Iteration   2: 8.121 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.162 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (8.121, 8.162, 8.201), stdev = 0.040
  CI (99.9%): [7.424, 8.900] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.306 ops/ms
# Warmup Iteration   2: 7.097 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 7.887 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.925 ±(99.9%) 0.627 ops/ms [Average]
  (min, avg, max) = (7.887, 7.925, 7.953), stdev = 0.034
  CI (99.9%): [7.298, 8.552] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.264 ops/ms
# Warmup Iteration   2: 5.500 ops/ms
# Warmup Iteration   3: 6.461 ops/ms
Iteration   1: 6.603 ops/ms
Iteration   2: 6.903 ops/ms
Iteration   3: 6.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.818 ±(99.9%) 3.423 ops/ms [Average]
  (min, avg, max) = (6.603, 6.818, 6.948), stdev = 0.188
  CI (99.9%): [3.395, 10.241] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.693 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.451 ±(99.9%) 0.004 ms/op
Iteration   1: 4.079 ±(99.9%) 0.009 ms/op
Iteration   2: 3.961 ±(99.9%) 0.008 ms/op
Iteration   3: 3.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.002 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.961, 4.002, 4.079), stdev = 0.066
  CI (99.9%): [2.798, 5.207] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 11.637 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.006 ms/op
Iteration   1: 3.725 ±(99.9%) 0.012 ms/op
Iteration   2: 3.889 ±(99.9%) 0.009 ms/op
Iteration   3: 3.744 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.786 ±(99.9%) 1.640 ms/op [Average]
  (min, avg, max) = (3.725, 3.786, 3.889), stdev = 0.090
  CI (99.9%): [2.146, 5.426] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.191 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.083 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.006 ms/op
Iteration   1: 4.162 ±(99.9%) 0.005 ms/op
Iteration   2: 4.124 ±(99.9%) 0.005 ms/op
Iteration   3: 3.957 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.081 ±(99.9%) 1.985 ms/op [Average]
  (min, avg, max) = (3.957, 4.081, 4.162), stdev = 0.109
  CI (99.9%): [2.096, 6.066] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.297 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.344 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.011 ms/op
Iteration   1: 4.757 ±(99.9%) 0.010 ms/op
Iteration   2: 4.731 ±(99.9%) 0.009 ms/op
Iteration   3: 4.548 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.679 ±(99.9%) 2.083 ms/op [Average]
  (min, avg, max) = (4.548, 4.679, 4.757), stdev = 0.114
  CI (99.9%): [2.596, 6.762] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.002 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.020 ms/op
Iteration   1: 3.995 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  13.139 ms/op
                 createUser·p0.9999: 28.375 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 3.921 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  25.685 ms/op
                 createUser·p0.9999: 30.535 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 4.036 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   7.479 ms/op
                 createUser·p0.999:  27.404 ms/op
                 createUser·p0.9999: 30.225 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240889
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 394 
    [ 2.500,  5.000) = 227849 
    [ 5.000,  7.500) = 10434 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 501 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 138 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     25.301 ms/op
     p(99.9900) =     30.078 ms/op
     p(99.9990) =     31.575 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 10.454 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.013 ms/op
Iteration   1: 4.039 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.853 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.897 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 22.842 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 3.877 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   7.766 ms/op
                 existUser·p0.999:  22.052 ms/op
                 existUser·p0.9999: 27.189 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   7.847 ms/op
                 existUser·p0.999:  15.139 ms/op
                 existUser·p0.9999: 28.296 ms/op
                 existUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243951
  mean =      3.930 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 305 
    [ 2.500,  5.000) = 229390 
    [ 5.000,  7.500) = 11122 
    [ 7.500, 10.000) = 2423 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.819 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.804 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.049 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.739 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.015 ms/op
Iteration   1: 3.985 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  24.142 ms/op
                 getUser·p0.9999: 30.900 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   2: 4.110 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.683 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   8.020 ms/op
                 getUser·p0.999:  12.599 ms/op
                 getUser·p0.9999: 28.424 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.967 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  27.484 ms/op
                 getUser·p0.9999: 30.435 ms/op
                 getUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238701
  mean =      4.020 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 224651 
    [ 5.000,  7.500) = 11020 
    [ 7.500, 10.000) = 1994 
    [10.000, 12.500) = 551 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 99 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     24.225 ms/op
     p(99.9900) =     30.356 ms/op
     p(99.9990) =     32.377 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.444 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.589 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.017 ms/op
Iteration   1: 4.803 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  27.113 ms/op
                 listUser·p0.9999: 32.910 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   2: 4.756 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.370 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 21.022 ms/op
                 listUser·p1.00:   21.758 ms/op

Iteration   3: 4.539 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.650 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  17.910 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204364
  mean =      4.696 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 176455 
    [ 5.000,  7.500) = 22268 
    [ 7.500, 10.000) = 4305 
    [10.000, 12.500) = 820 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     20.554 ms/op
     p(99.9900) =     31.509 ms/op
     p(99.9990) =     33.546 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.825 ± 4.980  ops/ms
ClientPb.existUser                       thrpt       3   8.162 ± 0.738  ops/ms
ClientPb.getUser                         thrpt       3   7.925 ± 0.627  ops/ms
ClientPb.listUser                        thrpt       3   6.818 ± 3.423  ops/ms
ClientPb.createUser                       avgt       3   4.002 ± 1.204   ms/op
ClientPb.existUser                        avgt       3   3.786 ± 1.640   ms/op
ClientPb.getUser                          avgt       3   4.081 ± 1.985   ms/op
ClientPb.listUser                         avgt       3   4.679 ± 2.083   ms/op
ClientPb.createUser                     sample  240889   3.983 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.602           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.301           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.078           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.375           ms/op
ClientPb.existUser                      sample  243951   3.930 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.540           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.819           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.139           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.787           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.245           ms/op
ClientPb.getUser                        sample  238701   4.020 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.155           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.292           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.954           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.225           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.356           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.128           ms/op
ClientPb.listUser                       sample  204364   4.696 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.554           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.817           ms/op
