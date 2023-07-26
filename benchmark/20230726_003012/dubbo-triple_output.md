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
# Warmup Iteration   1: 1.521 ops/ms
# Warmup Iteration   2: 3.436 ops/ms
# Warmup Iteration   3: 7.324 ops/ms
Iteration   1: 7.571 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.887 ±(99.9%) 5.292 ops/ms [Average]
  (min, avg, max) = (7.571, 7.887, 8.141), stdev = 0.290
  CI (99.9%): [2.595, 13.179] (assumes normal distribution)


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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 7.000 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.449 ±(99.9%) 3.362 ops/ms [Average]
  (min, avg, max) = (8.341, 8.449, 8.662), stdev = 0.184
  CI (99.9%): [5.087, 11.811] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.077 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 8.154 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 8.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.146 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (8.044, 8.146, 8.240), stdev = 0.098
  CI (99.9%): [6.350, 9.942] (assumes normal distribution)


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
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 4.911 ops/ms
# Warmup Iteration   3: 6.391 ops/ms
Iteration   1: 6.408 ops/ms
Iteration   2: 6.705 ops/ms
Iteration   3: 6.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.691 ±(99.9%) 5.059 ops/ms [Average]
  (min, avg, max) = (6.408, 6.691, 6.962), stdev = 0.277
  CI (99.9%): [1.633, 11.750] (assumes normal distribution)


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
# Warmup Iteration   1: 13.818 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.375 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.866 ±(99.9%) 0.014 ms/op
Iteration   2: 3.975 ±(99.9%) 0.010 ms/op
Iteration   3: 3.992 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.944 ±(99.9%) 1.249 ms/op [Average]
  (min, avg, max) = (3.866, 3.944, 3.992), stdev = 0.068
  CI (99.9%): [2.696, 5.193] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.681 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.005 ms/op
Iteration   1: 3.771 ±(99.9%) 0.005 ms/op
Iteration   2: 3.883 ±(99.9%) 0.007 ms/op
Iteration   3: 3.808 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.821 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.771, 3.821, 3.883), stdev = 0.057
  CI (99.9%): [2.780, 4.861] (assumes normal distribution)


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
# Warmup Iteration   1: 12.109 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.008 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
Iteration   3: 4.147 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.032 ±(99.9%) 1.898 ms/op [Average]
  (min, avg, max) = (3.945, 4.032, 4.147), stdev = 0.104
  CI (99.9%): [2.134, 5.930] (assumes normal distribution)


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
# Warmup Iteration   1: 15.155 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.795 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.930 ±(99.9%) 0.012 ms/op
Iteration   1: 4.911 ±(99.9%) 0.011 ms/op
Iteration   2: 4.709 ±(99.9%) 0.012 ms/op
Iteration   3: 4.649 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.757 ±(99.9%) 2.505 ms/op [Average]
  (min, avg, max) = (4.649, 4.757, 4.911), stdev = 0.137
  CI (99.9%): [2.252, 7.262] (assumes normal distribution)


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
# Warmup Iteration   1: 14.072 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.626 ±(99.9%) 0.021 ms/op
Iteration   1: 4.109 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.776 ms/op
                 createUser·p0.95:   5.423 ms/op
                 createUser·p0.99:   7.517 ms/op
                 createUser·p0.999:  24.283 ms/op
                 createUser·p0.9999: 34.201 ms/op
                 createUser·p1.00:   35.455 ms/op

Iteration   2: 4.070 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.042 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  14.500 ms/op
                 createUser·p0.9999: 33.198 ms/op
                 createUser·p1.00:   34.865 ms/op

Iteration   3: 3.982 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.620 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  28.229 ms/op
                 createUser·p0.9999: 32.439 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236840
  mean =      4.053 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 215 
    [ 2.500,  5.000) = 223837 
    [ 5.000,  7.500) = 10944 
    [ 7.500, 10.000) = 1248 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 48 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     33.172 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.981 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.011 ms/op
Iteration   1: 3.927 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.243 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  24.150 ms/op
                 existUser·p0.9999: 26.467 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   8.282 ms/op
                 existUser·p0.999:  12.840 ms/op
                 existUser·p0.9999: 28.982 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 4.018 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  15.840 ms/op
                 existUser·p0.9999: 32.586 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 238743
  mean =      4.020 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 298 
    [ 2.500,  5.000) = 222733 
    [ 5.000,  7.500) = 12108 
    [ 7.500, 10.000) = 2649 
    [10.000, 12.500) = 540 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     18.912 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     33.116 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 14.437 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 6.344 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 4.465 ±(99.9%) 0.016 ms/op
Iteration   1: 4.065 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.195 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  15.026 ms/op
                 getUser·p0.9999: 24.857 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 4.016 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  24.295 ms/op
                 getUser·p0.9999: 27.039 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.933 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.867 ms/op
                 getUser·p0.999:  12.541 ms/op
                 getUser·p0.9999: 26.341 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239528
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 229835 
    [ 5.000,  7.500) = 6037 
    [ 7.500, 10.000) = 2441 
    [10.000, 12.500) = 818 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     15.307 ms/op
     p(99.9900) =     26.511 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 15.902 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 5.542 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.018 ms/op
Iteration   1: 4.868 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   9.468 ms/op
                 listUser·p0.999:  25.381 ms/op
                 listUser·p0.9999: 28.391 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   2: 4.728 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  19.511 ms/op
                 listUser·p0.9999: 23.888 ms/op
                 listUser·p1.00:   25.919 ms/op

Iteration   3: 4.814 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.660 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 18.624 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199798
  mean =      4.803 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 165703 
    [ 5.000,  7.500) = 27891 
    [ 7.500, 10.000) = 4804 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      9.142 ms/op
     p(99.9000) =     19.445 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.887 ± 5.292  ops/ms
ClientPb.existUser                       thrpt       3   8.449 ± 3.362  ops/ms
ClientPb.getUser                         thrpt       3   8.146 ± 1.796  ops/ms
ClientPb.listUser                        thrpt       3   6.691 ± 5.059  ops/ms
ClientPb.createUser                       avgt       3   3.944 ± 1.249   ms/op
ClientPb.existUser                        avgt       3   3.821 ± 1.041   ms/op
ClientPb.getUser                          avgt       3   4.032 ± 1.898   ms/op
ClientPb.listUser                         avgt       3   4.757 ± 2.505   ms/op
ClientPb.createUser                     sample  236840   4.053 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.620           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.510           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.172           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.455           ms/op
ClientPb.existUser                      sample  238743   4.020 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.710           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.192           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.359           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  239528   4.004 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.579           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.735           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.520           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.307           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.460           ms/op
ClientPb.listUser                       sample  199798   4.803 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.242           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.142           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.445           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
