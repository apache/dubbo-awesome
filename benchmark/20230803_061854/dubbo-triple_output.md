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
# Warmup Iteration   1: 2.511 ops/ms
# Warmup Iteration   2: 6.183 ops/ms
# Warmup Iteration   3: 8.936 ops/ms
Iteration   1: 9.809 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.607 ±(99.9%) 7.447 ops/ms [Average]
  (min, avg, max) = (9.138, 9.607, 9.875), stdev = 0.408
  CI (99.9%): [2.161, 17.054] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.251 ops/ms
# Warmup Iteration   2: 8.808 ops/ms
# Warmup Iteration   3: 10.376 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.328 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (10.245, 10.328, 10.452), stdev = 0.109
  CI (99.9%): [8.335, 12.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.328 ops/ms
# Warmup Iteration   2: 9.123 ops/ms
# Warmup Iteration   3: 9.414 ops/ms
Iteration   1: 9.588 ops/ms
Iteration   2: 9.874 ops/ms
Iteration   3: 9.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.775 ±(99.9%) 2.954 ops/ms [Average]
  (min, avg, max) = (9.588, 9.775, 9.874), stdev = 0.162
  CI (99.9%): [6.821, 12.729] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.077 ops/ms
# Warmup Iteration   2: 7.382 ops/ms
# Warmup Iteration   3: 8.323 ops/ms
Iteration   1: 8.398 ops/ms
Iteration   2: 8.401 ops/ms
Iteration   3: 8.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.422 ±(99.9%) 0.697 ops/ms [Average]
  (min, avg, max) = (8.398, 8.422, 8.466), stdev = 0.038
  CI (99.9%): [7.725, 9.118] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.927 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.005 ms/op
Iteration   1: 3.359 ±(99.9%) 0.002 ms/op
Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
Iteration   3: 3.174 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.259 ±(99.9%) 1.705 ms/op [Average]
  (min, avg, max) = (3.174, 3.259, 3.359), stdev = 0.093
  CI (99.9%): [1.553, 4.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.930 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.003 ms/op
Iteration   1: 3.170 ±(99.9%) 0.005 ms/op
Iteration   2: 3.178 ±(99.9%) 0.004 ms/op
Iteration   3: 3.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.170 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (3.162, 3.170, 3.178), stdev = 0.008
  CI (99.9%): [3.020, 3.319] (assumes normal distribution)


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
# Warmup Iteration   1: 7.883 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.002 ms/op
Iteration   1: 3.274 ±(99.9%) 0.005 ms/op
Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
Iteration   3: 3.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.189 ±(99.9%) 1.468 ms/op [Average]
  (min, avg, max) = (3.114, 3.189, 3.274), stdev = 0.080
  CI (99.9%): [1.721, 4.657] (assumes normal distribution)


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
# Warmup Iteration   1: 9.036 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.008 ms/op
Iteration   1: 3.738 ±(99.9%) 0.005 ms/op
Iteration   2: 3.732 ±(99.9%) 0.009 ms/op
Iteration   3: 3.794 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.755 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.732, 3.755, 3.794), stdev = 0.034
  CI (99.9%): [3.136, 4.374] (assumes normal distribution)


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
# Warmup Iteration   1: 8.663 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.010 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  10.134 ms/op
                 createUser·p0.9999: 23.628 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   2: 3.188 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  20.731 ms/op
                 createUser·p0.9999: 25.558 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  17.036 ms/op
                 createUser·p0.9999: 27.207 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296831
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26693 
    [ 2.500,  5.000) = 263221 
    [ 5.000,  7.500) = 5823 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     25.799 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 6.771 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.008 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 20.892 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 22.315 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   3: 3.244 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 28.275 ms/op
                 existUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303963
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22946 
    [ 2.500,  5.000) = 275369 
    [ 5.000,  7.500) = 4283 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.468 ms/op
     p(99.9900) =     26.496 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


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
# Warmup Iteration   1: 8.502 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.570 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.010 ms/op
Iteration   1: 3.299 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.148 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  17.175 ms/op
                 getUser·p0.9999: 22.980 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  11.580 ms/op
                 getUser·p0.9999: 22.772 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  10.949 ms/op
                 getUser·p0.9999: 22.847 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294715
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17486 
    [ 2.500,  5.000) = 268464 
    [ 5.000,  7.500) = 7270 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 169 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     22.857 ms/op
     p(99.9990) =     23.859 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 9.420 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.799 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 26.659 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   2: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  13.502 ms/op
                 listUser·p0.9999: 21.922 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   7.462 ms/op
                 listUser·p0.999:  13.253 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253209
  mean =      3.792 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 244124 
    [ 5.000,  7.500) = 6567 
    [ 7.500, 10.000) = 1803 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 212 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      7.446 ms/op
     p(99.9000) =     14.526 ms/op
     p(99.9900) =     22.599 ms/op
     p(99.9990) =     27.519 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.607 ± 7.447  ops/ms
ClientPb.existUser                       thrpt       3  10.328 ± 1.993  ops/ms
ClientPb.getUser                         thrpt       3   9.775 ± 2.954  ops/ms
ClientPb.listUser                        thrpt       3   8.422 ± 0.697  ops/ms
ClientPb.createUser                       avgt       3   3.259 ± 1.705   ms/op
ClientPb.existUser                        avgt       3   3.170 ± 0.149   ms/op
ClientPb.getUser                          avgt       3   3.189 ± 1.468   ms/op
ClientPb.listUser                         avgt       3   3.755 ± 0.619   ms/op
ClientPb.createUser                     sample  296831   3.232 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.811           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.465           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.799           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.296           ms/op
ClientPb.existUser                      sample  303963   3.155 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.496           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.524           ms/op
ClientPb.getUser                        sample  294715   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.417           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.857           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.281           ms/op
ClientPb.listUser                       sample  253209   3.792 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.650           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.446           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.526           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.599           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.049           ms/op
