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
# Warmup Iteration   1: 1.651 ops/ms
# Warmup Iteration   2: 3.585 ops/ms
# Warmup Iteration   3: 6.880 ops/ms
Iteration   1: 7.481 ops/ms
Iteration   2: 7.752 ops/ms
Iteration   3: 7.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.600 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (7.481, 7.600, 7.752), stdev = 0.139
  CI (99.9%): [5.073, 10.128] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 2.080 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.665 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.993 ±(99.9%) 5.191 ops/ms [Average]
  (min, avg, max) = (7.665, 7.993, 8.174), stdev = 0.285
  CI (99.9%): [2.802, 13.183] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 6.513 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 7.482 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 7.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.818 ±(99.9%) 5.924 ops/ms [Average]
  (min, avg, max) = (7.482, 7.818, 8.130), stdev = 0.325
  CI (99.9%): [1.895, 13.742] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.908 ops/ms
# Warmup Iteration   2: 5.511 ops/ms
# Warmup Iteration   3: 6.322 ops/ms
Iteration   1: 6.362 ops/ms
Iteration   2: 6.346 ops/ms
Iteration   3: 6.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.364 ±(99.9%) 0.326 ops/ms [Average]
  (min, avg, max) = (6.346, 6.364, 6.382), stdev = 0.018
  CI (99.9%): [6.038, 6.689] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.600 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.860 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.008 ms/op
Iteration   1: 4.219 ±(99.9%) 0.009 ms/op
Iteration   2: 4.161 ±(99.9%) 0.006 ms/op
Iteration   3: 4.120 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.166 ±(99.9%) 0.902 ms/op [Average]
  (min, avg, max) = (4.120, 4.166, 4.219), stdev = 0.049
  CI (99.9%): [3.265, 5.068] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.197 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.007 ms/op
Iteration   1: 3.941 ±(99.9%) 0.007 ms/op
Iteration   2: 3.821 ±(99.9%) 0.005 ms/op
Iteration   3: 3.978 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.913 ±(99.9%) 1.491 ms/op [Average]
  (min, avg, max) = (3.821, 3.913, 3.978), stdev = 0.082
  CI (99.9%): [2.423, 5.404] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.542 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.893 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.004 ms/op
Iteration   1: 4.156 ±(99.9%) 0.005 ms/op
Iteration   2: 4.231 ±(99.9%) 0.006 ms/op
Iteration   3: 4.114 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.167 ±(99.9%) 1.074 ms/op [Average]
  (min, avg, max) = (4.114, 4.167, 4.231), stdev = 0.059
  CI (99.9%): [3.093, 5.241] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.885 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.598 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.970 ±(99.9%) 0.009 ms/op
Iteration   1: 4.867 ±(99.9%) 0.009 ms/op
Iteration   2: 4.785 ±(99.9%) 0.009 ms/op
Iteration   3: 4.835 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.829 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (4.785, 4.829, 4.867), stdev = 0.041
  CI (99.9%): [4.081, 5.578] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.408 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.695 ±(99.9%) 0.022 ms/op
Iteration   1: 4.158 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.825 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   8.716 ms/op
                 createUser·p0.999:  23.593 ms/op
                 createUser·p0.9999: 27.689 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   2: 4.055 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  13.206 ms/op
                 createUser·p0.9999: 28.482 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 4.097 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.733 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  28.604 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 233939
  mean =      4.103 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 409 
    [ 2.500,  5.000) = 218181 
    [ 5.000,  7.500) = 10547 
    [ 7.500, 10.000) = 3820 
    [10.000, 12.500) = 495 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     23.595 ms/op
     p(99.9900) =     30.874 ms/op
     p(99.9990) =     32.406 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.068 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.162 ±(99.9%) 0.015 ms/op
Iteration   1: 4.087 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.890 ms/op
                 existUser·p0.99:   8.348 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 4.030 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.745 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.266 ms/op
                 existUser·p0.999:  25.494 ms/op
                 existUser·p0.9999: 27.756 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   3: 4.030 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.431 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.723 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  17.531 ms/op
                 existUser·p0.9999: 31.656 ms/op
                 existUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237049
  mean =      4.049 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 368 
    [ 2.500,  5.000) = 218876 
    [ 5.000,  7.500) = 13044 
    [ 7.500, 10.000) = 3618 
    [10.000, 12.500) = 597 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.446 ms/op
     p(99.9000) =     18.838 ms/op
     p(99.9900) =     30.457 ms/op
     p(99.9990) =     32.109 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 12.486 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.929 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.016 ms/op
Iteration   1: 4.188 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   8.364 ms/op
                 getUser·p0.999:  25.613 ms/op
                 getUser·p0.9999: 37.814 ms/op
                 getUser·p1.00:   37.814 ms/op

Iteration   2: 4.089 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   8.782 ms/op
                 getUser·p0.999:  24.859 ms/op
                 getUser·p0.9999: 29.175 ms/op
                 getUser·p1.00:   30.671 ms/op

Iteration   3: 4.109 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  27.335 ms/op
                 getUser·p0.9999: 29.709 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232329
  mean =      4.128 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93 
    [ 2.500,  5.000) = 219135 
    [ 5.000,  7.500) = 9395 
    [ 7.500, 10.000) = 2666 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 143 
    [27.500, 30.000) = 105 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     30.209 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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
# Warmup Iteration   1: 14.798 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.768 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.081 ±(99.9%) 0.021 ms/op
Iteration   1: 5.077 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   7.602 ms/op
                 listUser·p0.99:   10.637 ms/op
                 listUser·p0.999:  26.313 ms/op
                 listUser·p0.9999: 29.629 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   2: 4.923 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  19.533 ms/op
                 listUser·p0.9999: 26.001 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   3: 4.850 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 20.310 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193900
  mean =      4.948 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 140964 
    [ 5.000,  7.500) = 45318 
    [ 7.500, 10.000) = 5720 
    [10.000, 12.500) = 938 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 280 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     20.352 ms/op
     p(99.9900) =     28.450 ms/op
     p(99.9990) =     30.365 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.600 ± 2.527  ops/ms
ClientPb.existUser                       thrpt       3   7.993 ± 5.191  ops/ms
ClientPb.getUser                         thrpt       3   7.818 ± 5.924  ops/ms
ClientPb.listUser                        thrpt       3   6.364 ± 0.326  ops/ms
ClientPb.createUser                       avgt       3   4.166 ± 0.902   ms/op
ClientPb.existUser                        avgt       3   3.913 ± 1.491   ms/op
ClientPb.getUser                          avgt       3   4.167 ± 1.074   ms/op
ClientPb.listUser                         avgt       3   4.829 ± 0.749   ms/op
ClientPb.createUser                     sample  233939   4.103 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.585           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.595           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.874           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.506           ms/op
ClientPb.existUser                      sample  237049   4.049 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.431           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.446           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.838           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.440           ms/op
ClientPb.getUser                        sample  232329   4.128 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.415           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.454           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.625           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.814           ms/op
ClientPb.listUser                       sample  193900   4.948 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.087           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.945           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.450           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.227           ms/op
