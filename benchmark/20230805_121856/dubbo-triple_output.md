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
# Warmup Iteration   1: 2.459 ops/ms
# Warmup Iteration   2: 6.164 ops/ms
# Warmup Iteration   3: 9.229 ops/ms
Iteration   1: 9.807 ops/ms
Iteration   2: 10.001 ops/ms
Iteration   3: 9.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.892 ±(99.9%) 1.807 ops/ms [Average]
  (min, avg, max) = (9.807, 9.892, 10.001), stdev = 0.099
  CI (99.9%): [8.084, 11.699] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 9.247 ops/ms
# Warmup Iteration   3: 10.320 ops/ms
Iteration   1: 9.910 ops/ms
Iteration   2: 9.843 ops/ms
Iteration   3: 10.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.008 ±(99.9%) 4.199 ops/ms [Average]
  (min, avg, max) = (9.843, 10.008, 10.271), stdev = 0.230
  CI (99.9%): [5.809, 14.207] (assumes normal distribution)


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
# Warmup Iteration   1: 3.159 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 9.599 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 10.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.961 ±(99.9%) 5.722 ops/ms [Average]
  (min, avg, max) = (9.599, 9.961, 10.146), stdev = 0.314
  CI (99.9%): [4.239, 15.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 7.825 ops/ms
# Warmup Iteration   3: 7.999 ops/ms
Iteration   1: 8.422 ops/ms
Iteration   2: 8.283 ops/ms
Iteration   3: 8.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.434 ±(99.9%) 2.846 ops/ms [Average]
  (min, avg, max) = (8.283, 8.434, 8.595), stdev = 0.156
  CI (99.9%): [5.587, 11.280] (assumes normal distribution)


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
# Warmup Iteration   1: 8.719 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.005 ms/op
Iteration   1: 3.253 ±(99.9%) 0.005 ms/op
Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
Iteration   3: 3.391 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.302 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (3.253, 3.302, 3.391), stdev = 0.077
  CI (99.9%): [1.895, 4.708] (assumes normal distribution)


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
# Warmup Iteration   1: 8.300 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.487 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.005 ms/op
Iteration   1: 3.243 ±(99.9%) 0.005 ms/op
Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
Iteration   3: 3.177 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.180 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.118, 3.180, 3.243), stdev = 0.062
  CI (99.9%): [2.042, 4.317] (assumes normal distribution)


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
# Warmup Iteration   1: 8.006 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.004 ms/op
Iteration   1: 3.216 ±(99.9%) 0.006 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.207 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.189, 3.204, 3.216), stdev = 0.014
  CI (99.9%): [2.955, 3.453] (assumes normal distribution)


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
# Warmup Iteration   1: 9.012 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.007 ms/op
Iteration   1: 3.800 ±(99.9%) 0.006 ms/op
Iteration   2: 3.744 ±(99.9%) 0.007 ms/op
Iteration   3: 3.690 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.690, 3.745, 3.800), stdev = 0.055
  CI (99.9%): [2.738, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 8.362 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.010 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  18.848 ms/op
                 createUser·p0.9999: 23.345 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.327 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  18.310 ms/op
                 createUser·p0.9999: 23.409 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  15.679 ms/op
                 createUser·p0.9999: 20.183 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295451
  mean =      3.247 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17801 
    [ 2.500,  5.000) = 270849 
    [ 5.000,  7.500) = 5148 
    [ 7.500, 10.000) = 1083 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     16.132 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.891 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 7.193 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.587 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 22.086 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  13.936 ms/op
                 existUser·p0.9999: 21.068 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.195 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301969
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17982 
    [ 2.500,  5.000) = 275726 
    [ 5.000,  7.500) = 6746 
    [ 7.500, 10.000) = 950 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     12.863 ms/op
     p(99.9900) =     24.399 ms/op
     p(99.9990) =     26.114 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 8.409 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.010 ms/op
Iteration   1: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   5.136 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  16.432 ms/op
                 getUser·p0.9999: 18.889 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   2: 3.370 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.121 ms/op
                 getUser·p0.999:  17.404 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.381 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 22.508 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286481
  mean =      3.350 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12197 
    [ 2.500,  5.000) = 262541 
    [ 5.000,  7.500) = 10132 
    [ 7.500, 10.000) = 1071 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     23.670 ms/op
     p(99.9990) =     26.359 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 9.885 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 25.231 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 3.797 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   3.985 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.767 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  13.273 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252214
  mean =      3.805 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 244097 
    [ 5.000,  7.500) = 5601 
    [ 7.500, 10.000) = 1579 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     23.753 ms/op
     p(99.9990) =     26.311 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.892 ± 1.807  ops/ms
ClientPb.existUser                       thrpt       3  10.008 ± 4.199  ops/ms
ClientPb.getUser                         thrpt       3   9.961 ± 5.722  ops/ms
ClientPb.listUser                        thrpt       3   8.434 ± 2.846  ops/ms
ClientPb.createUser                       avgt       3   3.302 ± 1.406   ms/op
ClientPb.existUser                        avgt       3   3.180 ± 1.137   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 0.249   ms/op
ClientPb.listUser                         avgt       3   3.745 ± 1.007   ms/op
ClientPb.createUser                     sample  295451   3.247 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.132           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.101           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.019           ms/op
ClientPb.existUser                      sample  301969   3.176 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.049           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.931           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.863           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.399           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.411           ms/op
ClientPb.getUser                        sample  286481   3.350 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.652           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.670           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.509           ms/op
ClientPb.listUser                       sample  252214   3.805 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.369           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.753           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.509           ms/op
