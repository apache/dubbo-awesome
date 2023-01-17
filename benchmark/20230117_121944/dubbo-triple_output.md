# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.296 ops/ms
# Warmup Iteration   2: 6.093 ops/ms
# Warmup Iteration   3: 8.750 ops/ms
Iteration   1: 9.272 ops/ms
Iteration   2: 9.142 ops/ms
Iteration   3: 9.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.237 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (9.142, 9.237, 9.298), stdev = 0.084
  CI (99.9%): [7.705, 10.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ops/ms
# Warmup Iteration   2: 8.885 ops/ms
# Warmup Iteration   3: 9.411 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 9.616 ops/ms
Iteration   3: 9.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.812 ±(99.9%) 3.115 ops/ms [Average]
  (min, avg, max) = (9.616, 9.812, 9.930), stdev = 0.171
  CI (99.9%): [6.697, 12.927] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ops/ms
# Warmup Iteration   2: 8.451 ops/ms
# Warmup Iteration   3: 8.697 ops/ms
Iteration   1: 9.100 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.214 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (9.100, 9.214, 9.298), stdev = 0.102
  CI (99.9%): [7.353, 11.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ops/ms
# Warmup Iteration   2: 7.238 ops/ms
# Warmup Iteration   3: 7.268 ops/ms
Iteration   1: 7.868 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 7.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.996 ±(99.9%) 3.624 ops/ms [Average]
  (min, avg, max) = (7.868, 7.996, 8.225), stdev = 0.199
  CI (99.9%): [4.373, 11.620] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.124 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.555 ±(99.9%) 0.006 ms/op
Iteration   1: 3.540 ±(99.9%) 0.006 ms/op
Iteration   2: 3.322 ±(99.9%) 0.007 ms/op
Iteration   3: 3.389 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.417 ±(99.9%) 2.034 ms/op [Average]
  (min, avg, max) = (3.322, 3.417, 3.540), stdev = 0.112
  CI (99.9%): [1.383, 5.451] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.451 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.005 ms/op
Iteration   1: 3.213 ±(99.9%) 0.009 ms/op
Iteration   2: 3.219 ±(99.9%) 0.011 ms/op
Iteration   3: 3.246 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.226 ±(99.9%) 0.313 ms/op [Average]
  (min, avg, max) = (3.213, 3.226, 3.246), stdev = 0.017
  CI (99.9%): [2.913, 3.539] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.004 ms/op
Iteration   1: 3.449 ±(99.9%) 0.008 ms/op
Iteration   2: 3.532 ±(99.9%) 0.005 ms/op
Iteration   3: 3.441 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.474 ±(99.9%) 0.920 ms/op [Average]
  (min, avg, max) = (3.441, 3.474, 3.532), stdev = 0.050
  CI (99.9%): [2.554, 4.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.291 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
Iteration   1: 4.056 ±(99.9%) 0.007 ms/op
Iteration   2: 3.985 ±(99.9%) 0.010 ms/op
Iteration   3: 3.822 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.954 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (3.822, 3.954, 4.056), stdev = 0.120
  CI (99.9%): [1.763, 6.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.084 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.861 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.414 ±(99.9%) 0.009 ms/op
Iteration   1: 3.641 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   5.308 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  22.151 ms/op
                 createUser·p0.9999: 27.722 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  23.101 ms/op
                 createUser·p0.9999: 26.339 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  18.148 ms/op
                 createUser·p0.9999: 26.306 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273995
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6650 
    [ 2.500,  5.000) = 258565 
    [ 5.000,  7.500) = 7696 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     26.581 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.525 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.009 ms/op
Iteration   1: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.092 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  9.500 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  20.581 ms/op
                 existUser·p0.9999: 24.523 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.177 ms/op
                 existUser·p0.999:  15.234 ms/op
                 existUser·p0.9999: 32.489 ms/op
                 existUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290340
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18707 
    [ 2.500,  5.000) = 266561 
    [ 5.000,  7.500) = 4024 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     32.079 ms/op
     p(99.9990) =     33.632 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.246 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.009 ms/op
Iteration   1: 3.566 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  21.037 ms/op
                 getUser·p0.9999: 23.101 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.560 ms/op
                 getUser·p0.999:  22.059 ms/op
                 getUser·p0.9999: 24.955 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 26.001 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279745
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7110 
    [ 2.500,  5.000) = 263031 
    [ 5.000,  7.500) = 8416 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     19.309 ms/op
     p(99.9900) =     24.708 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.124 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.013 ms/op
Iteration   1: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  20.809 ms/op
                 listUser·p0.9999: 24.159 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.154 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.401 ms/op
                 listUser·p0.9999: 17.715 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  17.201 ms/op
                 listUser·p0.9999: 20.349 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237139
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 226336 
    [ 5.000,  7.500) = 8479 
    [ 7.500, 10.000) = 1498 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.759 ms/op
     p(99.9900) =     23.111 ms/op
     p(99.9990) =     24.770 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.237 ± 1.532  ops/ms
ClientPb.existUser                       thrpt       3   9.812 ± 3.115  ops/ms
ClientPb.getUser                         thrpt       3   9.214 ± 1.861  ops/ms
ClientPb.listUser                        thrpt       3   7.996 ± 3.624  ops/ms
ClientPb.createUser                       avgt       3   3.417 ± 2.034   ms/op
ClientPb.existUser                        avgt       3   3.226 ± 0.313   ms/op
ClientPb.getUser                          avgt       3   3.474 ± 0.920   ms/op
ClientPb.listUser                         avgt       3   3.954 ± 2.191   ms/op
ClientPb.createUser                     sample  273995   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.992           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.940           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.581           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  290340   3.304 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.092           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.587           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.598           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  279745   3.430 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.198           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.309           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.708           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.345           ms/op
ClientPb.listUser                       sample  237139   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.915           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.111           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
